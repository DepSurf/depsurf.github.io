# Function: <code>ptep_test_and_clear_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307984,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:447",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307984,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307776,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:450",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307776,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323008,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:450",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323008,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320336,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:480",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320336,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579343653,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:480",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343424,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354853,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:485",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354640,
      "name": "ptep_test_and_clear_young",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382005,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:551",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381792,
      "name": "ptep_test_and_clear_young",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397477,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:538",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397264,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579400789,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:534",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400576,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410069,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409856,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410709,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410496,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413877,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413664,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476757,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476544,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554917,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554688,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661717,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:545",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661440,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675877,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:545",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675600,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710005,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:557",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709728,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
  "name": "ptep_test_and_clear_young",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492810420,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:718",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_clear_flush_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492817704,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:718",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493274580,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:718",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494066192,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:718",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
  "name": "ptep_test_and_clear_young",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226621248,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:62",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush_young"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878972,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:62",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3227517992,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:62",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272776446,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:370",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024886,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:370",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273556148,
      "name": "ptep_test_and_clear_young",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:370",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396693,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:534",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396480,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326181,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:534",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325968,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396613,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:534",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396400,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_test_and_clear_young",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405109,
      "name": "ptep_test_and_clear_young",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:534",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young",
        "arch/x86/mm/pgtable.c:ptep_clear_flush_young"
      ],
      "caller_func": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404896,
      "name": "ptep_test_and_clear_young",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ptep_test_and_clear_young(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
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
