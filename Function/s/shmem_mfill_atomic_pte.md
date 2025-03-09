# Function: <code>shmem_mfill_atomic_pte</code>

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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871248,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2248",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871248,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581005168,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2269",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005168,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1503
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082784,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2231",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082784,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145760,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2312",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145760,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203296,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203296,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393888,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2313",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393888,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581437408,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2355",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437408,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1567
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457808,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2343",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457808,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1685
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581728272,
      "name": "shmem_mfill_atomic_pte",
      "external": true,
      "loc": "mm/shmem.c:2346",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728272,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1183
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, bool wp_copy, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107360,
      "name": "shmem_mfill_atomic_pte",
      "external": true,
      "loc": "mm/shmem.c:2342",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107360,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, bool wp_copy, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581584,
      "name": "shmem_mfill_atomic_pte",
      "external": true,
      "loc": "mm/shmem.c:2400",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581584,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
int shmem_mfill_atomic_pte(pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio * * foliop)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788784,
      "name": "shmem_mfill_atomic_pte",
      "external": true,
      "loc": "mm/shmem.c:2433",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788784,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int shmem_mfill_atomic_pte(pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio * * foliop)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964032,
      "name": "shmem_mfill_atomic_pte",
      "external": true,
      "loc": "mm/shmem.c:2578",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964032,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492592824,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492592824,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1956
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226447344,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226447344,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285905472,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285905472,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2364
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272621880,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272621880,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172144,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172144,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118960,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118960,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1608
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163344,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163344,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
```

```json
{
  "name": "shmem_mfill_atomic_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229616,
      "name": "shmem_mfill_atomic_pte",
      "external": false,
      "loc": "mm/shmem.c:2332",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_zeropage_pte",
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229616,
      "name": "shmem_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1648
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
int shmem_mfill_atomic_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page * * pagep)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, pagep</code> ➡️ <code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, wp_copy, pagep</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>uffd_flags_t flags</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio * * foliop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool zeropage</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * * pagep</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, wp_copy, pagep</code> ➡️ <code>dst_pmd, dst_vma, dst_addr, src_addr, flags, foliop</code>
</li>
</ul>
</details>
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
