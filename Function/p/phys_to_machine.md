# Function: <code>phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594969150,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578970519,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595132080,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578967481,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595374750,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578969257,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578954175,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:205",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596301047,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:205",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578995177,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:205",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578956479,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602618821,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578998153,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578958975,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_pfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602786825,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001571,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578958142,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604580841,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000467,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965118,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604676145,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007891,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988880,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967582,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604688613,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010259,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991248,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976734,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609039803,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018211,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001008,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979342,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612103195,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020739,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002816,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578988462,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614242686,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023795,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186085,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579005214,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615162828,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042067,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:238",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048403,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579022067,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616929198,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064169,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050003,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627532852,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096025,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050003,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619277748,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095721,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte"
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
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579075331,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621570084,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121513,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:230",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967582,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604614894,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010611,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991600,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967518,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604692709,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010195,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991184,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```

```json
{
  "name": "phys_to_machine",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968110,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604692665,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013411,
      "name": "phys_to_machine",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992384,
      "name": "phys_to_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```
</details>
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys)
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
xmaddr_t phys_to_machine(xpaddr_t phys)
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
