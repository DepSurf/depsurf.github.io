# Function: <code>do_remap_gfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_remap_gfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * gfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, struct page * * pages)
```

```json
{
  "name": "do_remap_gfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988704,
      "name": "do_remap_gfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:2810",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_remap_domain_gfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988704,
      "name": "do_remap_gfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int do_remap_gfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * gfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, struct page * * pages)
```

```json
{
  "name": "do_remap_gfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578985376,
      "name": "do_remap_gfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:2800",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_remap_domain_gfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578985376,
      "name": "do_remap_gfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int do_remap_gfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * gfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, struct page * * pages)
```

```json
{
  "name": "do_remap_gfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987248,
      "name": "do_remap_gfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:2800",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_remap_domain_gfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987248,
      "name": "do_remap_gfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remap_gfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578952944,
      "name": "do_remap_gfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:94",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_remap_domain_gfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952944,
      "name": "do_remap_gfn.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_remap_gfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955200,
      "name": "do_remap_gfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:94",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_remap_domain_gfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955200,
      "name": "do_remap_gfn.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int do_remap_gfn(struct vm_area_struct * vma, long unsigned int addr, xen_pfn_t * gfn, int nr, int * err_ptr, pgprot_t prot, unsigned int domid, struct page * * pages)
```
</details>
</li>
</ul>
