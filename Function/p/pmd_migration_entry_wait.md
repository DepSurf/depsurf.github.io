# Function: <code>pmd_migration_entry_wait</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257264,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:357",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257264,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403440,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:358",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403440,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486928,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:356",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486928,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595072,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:354",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595072,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665632,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665632,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887136,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:360",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887136,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933040,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:356",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933040,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958432,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:330",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958432,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263168,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:338",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263168,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582731472,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:341",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731472,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252096,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:356",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252096,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583471568,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:361",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583471568,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663872,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:364",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663872,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
  "name": "pmd_migration_entry_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/hmm.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/hmm.c",
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286583008,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286583008,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
  "name": "pmd_migration_entry_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_migration_entry_wait",
      "external": false,
      "loc": "include/linux/swapops.h:288",
      "file": "mm/hmm.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634368,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634368,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575376,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575376,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625680,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625680,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```

```json
{
  "name": "pmd_migration_entry_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692032,
      "name": "pmd_migration_entry_wait",
      "external": true,
      "loc": "mm/migrate.c:355",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692032,
      "name": "pmd_migration_entry_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```
</details>
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
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
void pmd_migration_entry_wait(struct mm_struct * mm, pmd_t * pmd)
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
