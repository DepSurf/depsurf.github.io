# Function: <code>tlb_finish_mmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666528,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:271",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:unmap_region",
        "mm/mmap.c:exit_mmap",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666528,
      "name": "tlb_finish_mmu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776544,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:275",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776544,
      "name": "tlb_finish_mmu",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841312,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:275",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841312,
      "name": "tlb_finish_mmu",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886864,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:414",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886864,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981248,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:415",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981248,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116016,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/memory.c:430",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116016,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257936,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:247",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257936,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332384,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332384,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391792,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391792,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588992,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:299",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588992,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634944,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:299",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634944,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656560,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:312",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656560,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924752,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:312",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924752,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331552,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:325",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/mempolicy.c:change_prot_numa",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331552,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582831968,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:363",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/mempolicy.c:change_prot_numa",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582831968,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047360,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:363",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/mempolicy.c:change_prot_numa",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047360,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void tlb_finish_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229200,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:364",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:free_ldt_pgtables",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/mempolicy.c:change_prot_numa",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229200,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492797368,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492797368,
      "name": "tlb_finish_mmu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226611688,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "fs/exec.c:setup_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226611688,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286168624,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286168624,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272764812,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272764812,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360640,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360640,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304352,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304352,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351840,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351840,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tlb_finish_mmu(struct mmu_gather * tlb, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "tlb_finish_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415776,
      "name": "tlb_finish_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:243",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:unmap_hugepage_range",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415776,
      "name": "tlb_finish_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
