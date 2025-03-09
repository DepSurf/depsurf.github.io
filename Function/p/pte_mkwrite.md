# Function: <code>pte_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578986895,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580680361,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715217,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790737,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580880540,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580973537,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578983615,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580793853,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830607,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926318,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008170,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033388,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127400,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578985487,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580857430,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896184,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994618,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082194,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108576,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202442,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:242",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578993631,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580798640,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900980,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940919,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042043,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130908,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147096,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250508,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:299",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996607,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872141,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997882,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041068,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152271,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244930,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281625,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382275,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:314",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578999967,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581006098,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132022,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176548,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295570,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390086,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531955,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:324",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578998863,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581083359,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213530,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259904,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378785,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473782,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501955,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617714,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:326",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579006336,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581146344,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283587,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333637,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489767,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589159,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611593,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729805,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579007840,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581203880,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342307,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393045,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554241,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652823,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682505,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581803357,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579015840,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581394375,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525077,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591203,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764947,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870849,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901039,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:365",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579018368,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581437893,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582726,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637219,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812949,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917133,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946565,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579021600,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581458293,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604318,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658862,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841047,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942104,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972494,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:364",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040304,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870510,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927134,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132404,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247837,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275144,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:335",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061734,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266227,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334267,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579438,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744153,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582758435,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925878,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:338",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627535748,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_release_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757792,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835986,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107053,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275824,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583292366,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481455,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:355",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619282052,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_release_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973187,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583316785,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465329,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492182,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:356",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
pte_t pte_mkwrite(pte_t pte, struct vm_area_struct * vma)
```

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712480,
      "name": "pte_mkwrite",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:888",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/mprotect.c:change_pte_range",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712480,
      "name": "pte_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492593444,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492748480,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492799364,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492991352,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:make_huge_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493135728,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493269092,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:145",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226447980,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:286",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226579828,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:286",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612660,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:286",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226802120,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:286",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226876024,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:286",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285906252,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286093504,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286170148,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286411660,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286560300,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286637932,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286794276,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:655",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272622324,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272732044,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765476,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272889298,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272950094,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022000,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:254",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579008192,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581172728,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311155,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361893,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522977,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621559,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651241,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772093,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119539,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581242026,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306338,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464994,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562865,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589812,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710538,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579007776,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581163928,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302355,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353093,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514289,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612871,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642553,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763405,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "pte_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579010912,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581230200,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366335,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417029,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579303,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680471,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708937,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581832198,
      "name": "pte_mkwrite",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
pte_t pte_mkwrite(pte_t pte, struct vm_area_struct * vma)
```
</details>
</li>
</ul>
