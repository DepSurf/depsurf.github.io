# Function: <code>__xen_pgd_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969264,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:610",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969264,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966192,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:611",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966192,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968000,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:611",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968000,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578976640,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:636",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976640,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979840,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:612",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979840,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982816,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:636",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982816,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578980704,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980704,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987712,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987712,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990080,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990080,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001744,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001744,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579003552,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:597",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003552,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012576,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:597",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012576,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:597",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030816,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071592048810,
      "name": "__xen_pgd_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:601",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050880,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071593815001,
      "name": "__xen_pgd_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:601",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081872,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071595957130,
      "name": "__xen_pgd_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:617",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080608,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071596474425,
      "name": "__xen_pgd_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, void (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:617",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106384,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071597369766,
      "name": "__xen_pgd_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990432,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990432,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990016,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990016,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```

```json
{
  "name": "__xen_pgd_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578991216,
      "name": "__xen_pgd_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:645",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991216,
      "name": "__xen_pgd_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(struct mm_struct *, struct page *, enum pt_level) func</code> ➡️ <code>void (*)(struct mm_struct *, struct page *, enum pt_level) func</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int __xen_pgd_walk(struct mm_struct * mm, pgd_t * pgd, int (*)(struct mm_struct *, struct page *, enum pt_level) func, long unsigned int limit)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
