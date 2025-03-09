# Function: <code>get_task_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580812256,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:126",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812256,
      "name": "get_task_policy.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071580814640,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937099,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:125",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935872,
      "name": "get_task_policy.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071580940032,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581008845,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:125",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004800,
      "name": "get_task_policy.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581010768,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052636,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:128",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052224,
      "name": "get_task_policy.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581058272,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163772,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163360,
      "name": "get_task_policy.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581169296,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307038,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306736,
      "name": "get_task_policy.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581313808,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581389982,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389664,
      "name": "get_task_policy.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581397712,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581501695,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501216,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581509824,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581566063,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565584,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581574192,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581795582,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:156",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787472,
      "name": "get_task_policy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581843486,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:156",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/hugetlb.c:allowed_mems_nr",
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832416,
      "name": "get_task_policy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874331,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:156",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863264,
      "name": "get_task_policy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582165729,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:158",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154544,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582622858,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:161",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609760,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147178,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:161",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132704,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583357496,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:161",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342944,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588410,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:166",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:folio_alloc",
        "mm/mempolicy.c:folio_alloc",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:vma_policy_mof",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/zswap.c:zswap_writeback_entry",
        "fs/proc/task_mmu.c:hold_task_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579120,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493007944,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493006392,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446603336493010448,
      "name": "get_task_policy",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286430100,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286429264,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055286437584,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581534799,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534320,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581542928,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581476559,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476080,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581484576,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581526111,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525632,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581534240,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
```

```json
{
  "name": "get_task_policy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581591391,
      "name": "get_task_policy",
      "external": true,
      "loc": "mm/mempolicy.c:130",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ],
      "caller_func": [
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:vma_policy_mof"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590912,
      "name": "get_task_policy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581599312,
      "name": "get_task_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct mempolicy * get_task_policy(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct mempolicy * get_task_policy(struct task_struct * p)
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
