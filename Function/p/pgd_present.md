# Function: <code>pgd_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579278979,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320246,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580841738,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581481390,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294243,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335462,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580905058,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912282,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581562065,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:664",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_present(pgd_t pgd)
```

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609041656,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331721,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390520,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579397000,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609172454,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541541,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605073,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616270,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762353,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914456,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992695,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458508,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:938",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394038,
      "name": "pgd_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_present(pgd_t pgd)
```

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612105014,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333305,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394840,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579403368,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584725,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652220,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663262,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810433,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961336,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042263,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515420,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266666,
      "name": "pgd_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_present(pgd_t pgd)
```

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614244761,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336040,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398341,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579406624,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606968,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673192,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685321,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838878,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987323,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068745,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545049,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:937",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208986,
      "name": "pgd_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_present(pgd_t pgd)
```

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615164837,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391360,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460581,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579469177,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874088,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942525,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954776,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129742,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289402,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382809,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861161,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:908",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082624,
      "name": "pgd_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_present(pgd_t pgd)
```

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616930836,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457881,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536504,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579546069,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272327,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352122,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370024,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576750,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773851,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885480,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431689,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:906",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533056,
      "name": "pgd_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627536732,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547038,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596433402,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645304,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764375,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853420,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871496,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095646,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435096,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584019689,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:924",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619282716,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562334,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596974170,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659720,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980730,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069804,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088331,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305489,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650091,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584238767,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:925",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621575148,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589870,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597902602,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693704,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156010,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251706,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270763,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543361,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845005,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584450880,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1147",
      "file": "fs/userfaultfd.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:29",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:29",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:29",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:29",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297809548,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286110188,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183724,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286195984,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286629160,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745584,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287412936,
      "name": "pgd_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:964",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_present",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:24",
      "file": "fs/userfaultfd.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pgd_present(pgd_t pgd)
```
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int pgd_present(pgd_t pgd)
```
</details>
</li>
</ul>
