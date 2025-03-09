# Function: <code>hugetlb_mfill_atomic_pte</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int hugetlb_mfill_atomic_pte(pte_t * dst_pte, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio * * foliop)
```

```json
{
  "name": "hugetlb_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_mfill_atomic_pte",
      "external": true,
      "loc": "mm/hugetlb.c:6261",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596564362,
      "name": "hugetlb_mfill_atomic_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071583301456,
      "name": "hugetlb_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1414
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
int hugetlb_mfill_atomic_pte(pte_t * dst_pte, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio * * foliop)
```

```json
{
  "name": "hugetlb_mfill_atomic_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_mfill_atomic_pte",
      "external": true,
      "loc": "mm/hugetlb.c:6574",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597469804,
      "name": "hugetlb_mfill_atomic_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583538672,
      "name": "hugetlb_mfill_atomic_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1952
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int hugetlb_mfill_atomic_pte(pte_t * dst_pte, struct vm_area_struct * dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio * * foliop)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
