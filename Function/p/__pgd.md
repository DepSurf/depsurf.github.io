# Function: <code>__pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578968816,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pgd_alloc",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594996479,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220503,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595063765,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289989,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667931,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746629,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587362041,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595142614,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_pgd_alloc",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595159964,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220746,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595229463,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290090,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587852017,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595243536,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580788862,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865845,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863538,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580173,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:405",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595385284,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_pgd_alloc",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595402539,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232900,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595472513,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305514,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588066778,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595487578,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853230,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907813,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078244,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764845,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596306579,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596322001,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230505,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596394146,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303406,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329560,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293572,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898415,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953269,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304685,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586888133,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594802,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624505,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602639955,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246075,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602712796,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325091,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579354729,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858639,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602721977,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000514,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055013,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588870049,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587376977,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763149,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602793207,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602809598,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258521,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602885431,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336534,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579366275,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237772,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382653,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134129,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193733,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249023,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680834,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557242,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604587072,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604604640,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282185,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480607,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363078,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579393869,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481810,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410223,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210561,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277013,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491309,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811570,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651576,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682454,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700235,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296450,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940219,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377649,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579409830,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941499,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426013,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286721,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351462,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952283,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117282,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663848,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694902,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604712619,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302002,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590167771,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381937,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413014,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169051,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429181,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345441,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410966,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179817,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322914,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate.c",
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
pgd_t __pgd(pgdval_t val)
```

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870953,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579002440,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579331791,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390625,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579422000,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453956,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579454278,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519228,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610928,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800275,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591143282,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:401",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870953,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071578998928,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393590,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579453956,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581800275,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
pgd_t __pgd(pgdval_t val)
```

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238322,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579004328,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579333375,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394945,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579421410,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591272890,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579451142,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560634,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591332687,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591227042,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238322,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579000752,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266280,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591272890,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591332687,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
pgd_t __pgd(pgdval_t val)
```

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591181139,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579014296,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579336125,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398445,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579424521,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215770,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579453648,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584665,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275387,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591176284,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181139,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185750,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208591,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591215770,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591275387,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
pgd_t __pgd(pgdval_t val)
```

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592037284,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579032612,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579391435,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460684,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579488146,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092379,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579519017,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850361,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216053,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592029980,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037284,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592047922,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082229,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592092379,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592216053,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
pgd_t __pgd(pgdval_t val)
```

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593803309,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579052980,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579457949,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536610,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579568139,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859446,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579603136,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593968906,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582242358,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593994725,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593797809,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803309,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579046464,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532368,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071593859446,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071593968906,
      "name": "__pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071593994725,
      "name": "__pgd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491445,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627541499,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547106,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627715744,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676379,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439744,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716114,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634966,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582733023,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153350,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595741924,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:408",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235573,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619287675,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562402,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619473216,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690251,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980556,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729698,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844166,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582949503,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363782,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596267892,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525653,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621580171,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589938,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621769696,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724779,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908988,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764642,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018694,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583128975,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pgd_populate",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600454,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597150580,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590120,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604621183,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604638909,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297810,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770059,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377841,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579408854,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771339,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425021,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314289,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379814,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782105,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926562,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate.c",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667944,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698998,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604716701,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299010,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213467,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377761,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579408774,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214747,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424941,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305489,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371014,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225513,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259970,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate.c",
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
  "name": "__pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667949,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604699004,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_pgd_alloc",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604716731,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307842,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590263835,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386241,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417638,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265115,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434125,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369489,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434902,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275871,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395490,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/power/hibernate.c",
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
pgd_t __pgd(pgdval_t val)
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
pgd_t __pgd(pgdval_t val)
```
</details>
</li>
</ul>
