# Function: <code>__pti_set_user_pgtbl</code>

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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410928,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:131",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410928,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426656,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426656,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429904,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429904,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455568,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455568,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452432,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452432,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454704,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454704,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520112,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520112,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604288,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604288,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717792,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717792,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731360,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731360,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766304,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_pgd",
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766304,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425744,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425744,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354318,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/kaslr.c:init_trampoline",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range",
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354864,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425664,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425664,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__pti_set_user_pgtbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434848,
      "name": "__pti_set_user_pgtbl",
      "external": true,
      "loc": "arch/x86/mm/pti.c:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_set_p4d",
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434848,
      "name": "__pti_set_user_pgtbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t * pgdp, pgd_t pgd)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
