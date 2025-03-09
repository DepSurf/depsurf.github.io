# Function: <code>follow_pte_pmd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838800,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:3834",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838800,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884384,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4123",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884384,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978112,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4301",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978112,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113248,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4346",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113248,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192304,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4136",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192304,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265168,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4187",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265168,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324016,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324016,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522128,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4577",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522128,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492730240,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492730240,
      "name": "follow_pte_pmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226561076,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226561076,
      "name": "follow_pte_pmd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286076528,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286076528,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272722012,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272722012,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292864,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292864,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237296,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237296,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284064,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284064,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_pte_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348016,
      "name": "follow_pte_pmd",
      "external": true,
      "loc": "mm/memory.c:4212",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348016,
      "name": "follow_pte_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int * end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, ptepp, pmdpp, ptlp</code> ➡️ <code>mm, address, start, end, ptepp, pmdpp, ptlp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier_range * range</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, start, end, ptepp, pmdpp, ptlp</code> ➡️ <code>mm, address, range, ptepp, pmdpp, ptlp</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
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
