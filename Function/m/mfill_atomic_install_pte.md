# Function: <code>mfill_atomic_install_pte</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int mfill_atomic_install_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, bool wp_copy)
```

```json
{
  "name": "mfill_atomic_install_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411968,
      "name": "mfill_atomic_install_pte",
      "external": true,
      "loc": "mm/userfaultfd.c:57",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411968,
      "name": "mfill_atomic_install_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int mfill_atomic_install_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, bool wp_copy)
```

```json
{
  "name": "mfill_atomic_install_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925104,
      "name": "mfill_atomic_install_pte",
      "external": true,
      "loc": "mm/userfaultfd.c:58",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925104,
      "name": "mfill_atomic_install_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
int mfill_atomic_install_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, bool wp_copy)
```

```json
{
  "name": "mfill_atomic_install_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583480752,
      "name": "mfill_atomic_install_pte",
      "external": true,
      "loc": "mm/userfaultfd.c:58",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480752,
      "name": "mfill_atomic_install_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1175
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
int mfill_atomic_install_pte(pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, uffd_flags_t flags)
```

```json
{
  "name": "mfill_atomic_install_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583697344,
      "name": "mfill_atomic_install_pte",
      "external": true,
      "loc": "mm/userfaultfd.c:54",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697344,
      "name": "mfill_atomic_install_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1073
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
int mfill_atomic_install_pte(pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, uffd_flags_t flags)
```

```json
{
  "name": "mfill_atomic_install_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583891728,
      "name": "mfill_atomic_install_pte",
      "external": true,
      "loc": "mm/userfaultfd.c:70",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891728,
      "name": "mfill_atomic_install_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int mfill_atomic_install_pte(struct mm_struct * dst_mm, pmd_t * dst_pmd, struct vm_area_struct * dst_vma, long unsigned int dst_addr, struct page * page, bool newly_allocated, bool wp_copy)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<b>Param removed. </b>
<code>struct mm_struct * dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, page, newly_allocated, wp_copy</code> ➡️ <code>dst_pmd, dst_vma, dst_addr, page, newly_allocated, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
