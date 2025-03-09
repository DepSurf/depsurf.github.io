# Function: <code>xen_pud_walk</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578976661,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:577",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979865,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:557",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578983089,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:581",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980947,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578987965,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990333,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int xen_pud_walk(struct mm_struct * mm, pud_t * pud, int (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000704,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000704,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579002128,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:547",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002128,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012128,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:547",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012128,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579030368,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:547",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579030368,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050416,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:551",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050416,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081392,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:551",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081392,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579080128,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:567",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080128,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
void xen_pud_walk(struct mm_struct * mm, pud_t * pud, void (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105904,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:567",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105904,
      "name": "xen_pud_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990685,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990269,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pud_walk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991469,
      "name": "xen_pud_walk",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:590",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int xen_pud_walk(struct mm_struct * mm, pud_t * pud, int (*)(struct mm_struct *, struct page *, enum pt_level) func, bool last, long unsigned int limit)
```
</details>
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
