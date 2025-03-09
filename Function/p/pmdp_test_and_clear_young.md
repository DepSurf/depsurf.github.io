# Function: <code>pmdp_test_and_clear_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579308032,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:463",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308032,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307912,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:466",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306400,
      "name": "pmdp_test_and_clear_young.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579307824,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323144,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:466",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321904,
      "name": "pmdp_test_and_clear_young.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579323056,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320536,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:496",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319168,
      "name": "pmdp_test_and_clear_young.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579320384,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579343727,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:493",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343488,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354688,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:498",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354688,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381840,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:564",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381840,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397312,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:551",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397312,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579400624,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400624,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410117,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:554",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409904,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410757,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:554",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410544,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413925,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:554",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413712,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476805,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:554",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476592,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554981,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:554",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554752,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661797,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:558",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661520,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675957,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:558",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675680,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710085,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:570",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709808,
      "name": "pmdp_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492810420,
      "name": "pmdp_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:748",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_clear_flush_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493274744,
      "name": "pmdp_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:748",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494066192,
      "name": "pmdp_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:748",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmdp_test_and_clear_young",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:91",
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
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282756128,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:55",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282756128,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmdp_test_and_clear_young",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:91",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396528,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396528,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326016,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326016,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396448,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396448,
      "name": "pmdp_test_and_clear_young",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579404944,
      "name": "pmdp_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404944,
      "name": "pmdp_test_and_clear_young",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pmdp_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pmd_t * pmdp)
```
</details>
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
