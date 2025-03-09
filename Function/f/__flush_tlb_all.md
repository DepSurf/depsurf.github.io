# Function: <code>__flush_tlb_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595063322,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:125",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358495,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:125",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579288853,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:125",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_range",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313589,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:125",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579340800,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:125",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358495,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579340800,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595229031,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365372,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579300609,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__cpa_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312809,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579347001,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071586417282,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580715,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365372,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071579346112,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595472073,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383468,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579316073,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__cpa_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328006,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579362981,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071586626479,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765391,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:189",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383468,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579361952,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596393291,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291293,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579313360,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__cpa_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322582,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356337,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071586750367,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888565,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:204",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291293,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579354704,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602711938,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311036,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579336020,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__cpa_flush_range",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345734,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602725106,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384750,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071587234961,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377438,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:425",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311036,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579380992,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602884505,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322546,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579346984,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__cpa_flush_range",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357413,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602896582,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400447,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071587681284,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:470",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322546,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579400447,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604681515,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360005,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579384613,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693891,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430997,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071587820509,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:458",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359296,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579430997,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604781002,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388530,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579400149,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793910,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446965,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071588123613,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:460",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373888,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579446965,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604806769,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391858,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579403461,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819633,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451173,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071588328413,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378176,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579451173,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412869,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1167",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__kernel_map_pages",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412816,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413493,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1103",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413536,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416341,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1147",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416384,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479285,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1206",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479328,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558021,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1176",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558112,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665189,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1200",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665296,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679328,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1221",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679328,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713776,
      "name": "__flush_tlb_all",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1230",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713776,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224453144,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:350",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_tlb.c:flush_tlb_all"
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
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604720711,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387762,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579399365,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733513,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447013,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071587935197,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374080,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579447013,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604688649,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317122,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579328821,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701134,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375973,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071587648550,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304272,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579375973,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604798278,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387682,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579399285,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811080,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446933,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071588266973,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374000,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579446933,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __flush_tlb_all()
```

```json
{
  "name": "__flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604810897,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396201,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__kernel_map_pages",
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579407781,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823790,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579456485,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071588402141,
      "name": "__flush_tlb_all",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:476",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382480,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579456485,
      "name": "__flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
void __flush_tlb_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __flush_tlb_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __flush_tlb_all()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __flush_tlb_all()
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
