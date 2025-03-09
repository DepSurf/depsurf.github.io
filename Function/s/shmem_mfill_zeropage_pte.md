# Function: <code>shmem_mfill_zeropage_pte</code>

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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887600,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2369",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887600,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023888,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2390",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023888,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101648,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2374",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101648,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166000,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2455",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166000,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223920,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223920,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411504,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2447",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411504,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453648,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2489",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453648,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474544,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2487",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474544,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492610248,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492610248,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226464444,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464444,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285929136,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285929136,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272639352,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639352,
      "name": "shmem_mfill_zeropage_pte",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192768,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192768,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139520,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139520,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183968,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183968,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
```

```json
{
  "name": "shmem_mfill_zeropage_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247216,
      "name": "shmem_mfill_zeropage_pte",
      "external": true,
      "loc": "mm/shmem.c:2475",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247216,
      "name": "shmem_mfill_zeropage_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr)
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
