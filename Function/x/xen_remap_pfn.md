# Function: <code>xen_remap_pfn</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578986032,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2730",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986032,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990048,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2717",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990048,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578992800,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2715",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992800,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579003392,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2715",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003392,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579005456,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2397",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579005456,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579013344,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2396",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013344,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579031600,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579031600,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051584,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2425",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051584,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082832,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2425",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082832,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082976,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2433",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082976,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108768,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108768,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578993152,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2715",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993152,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578992736,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2715",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992736,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```

```json
{
  "name": "xen_remap_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578994096,
      "name": "xen_remap_pfn",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:2715",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994096,
      "name": "xen_remap_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct page * * pages</code>
</li>
</ul>
</details>
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
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
int xen_remap_pfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * pfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page * * pages)
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
