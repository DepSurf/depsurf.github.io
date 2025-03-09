# Function: <code>vma_mmu_pagesize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795920,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:653",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795920,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919392,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:656",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919392,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987536,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:656",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987536,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581045289,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:658",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033488,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581155806,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:659",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143232,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286304,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:652",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286304,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369216,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:652",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369216,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480544,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:654",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480544,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544960,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544960,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754320,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:794",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754320,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802432,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:824",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802432,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829424,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:831",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829424,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116928,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:833",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116928,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582561328,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:850",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561328,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 73
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075072,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:994",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075072,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 70
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285616,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:988",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285616,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 70
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583525056,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:1019",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583525056,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 70
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492978048,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492978048,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "vma_mmu_pagesize",
      "external": false,
      "loc": "include/linux/hugetlb.h:664",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "vma_mmu_pagesize",
      "external": false,
      "loc": "include/linux/hugetlb.h:664",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282844928,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "arch/powerpc/mm/hugetlbpage.c:550",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282844928,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272884070,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272884070,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 58
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513696,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513696,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455888,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455888,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505008,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505008,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_mmu_pagesize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570000,
      "name": "vma_mmu_pagesize",
      "external": true,
      "loc": "mm/hugetlb.c:655",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:huge_pmd_share",
        "fs/userfaultfd.c:handle_userfault",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570000,
      "name": "vma_mmu_pagesize",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 49
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct * vma)
```
</details>
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
