# Function: <code>follow_invalidate_pte</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int follow_invalidate_pte(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_invalidate_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595952,
      "name": "follow_invalidate_pte",
      "external": true,
      "loc": "mm/memory.c:4721",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595952,
      "name": "follow_invalidate_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
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
int follow_invalidate_pte(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_invalidate_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618592,
      "name": "follow_invalidate_pte",
      "external": true,
      "loc": "mm/memory.c:4748",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618592,
      "name": "follow_invalidate_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int follow_invalidate_pte(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "follow_invalidate_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_invalidate_pte",
      "external": true,
      "loc": "mm/memory.c:4894",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592199706,
      "name": "follow_invalidate_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581886240,
      "name": "follow_invalidate_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int follow_invalidate_pte(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int follow_invalidate_pte(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
</ul>
