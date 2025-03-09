# Function: <code>lookup_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292432,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:367",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/mm/mmio-mod.c:pre",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292432,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296241,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:373",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291936,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579311731,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:373",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307360,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579309359,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:402",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305136,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331751,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:402",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327008,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342750,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:422",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337920,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579364574,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:606",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364464,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579388649,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379008,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579391977,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383296,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432370,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:624",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:add_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/mmio-mod.c:print_pte",
        "arch/x86/mm/pti.c:pti_setup_vsyscall",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423344,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431794,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:624",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:add_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/mmio-mod.c:print_pte",
        "arch/x86/mm/pti.c:pti_setup_vsyscall",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423040,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434754,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:632",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426032,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498979,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:632",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite",
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_unprotect",
        "mm/kfence/core.c:kfence_protect",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088192,
      "name": "lookup_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579489696,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580435,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:635",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite",
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall",
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_protect_page",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855116,
      "name": "lookup_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579569792,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579690003,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:710",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall",
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_protect_page",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969802,
      "name": "lookup_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579678112,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703763,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:711",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall",
        "mm/kfence/core.c:kfence_init_pool",
        "mm/kfence/core.c:kfence_init_pool",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487392,
      "name": "lookup_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579691968,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738371,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:711",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd_init",
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597384014,
      "name": "lookup_address.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579726496,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387881,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379200,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317225,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308976,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387801,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379120,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```

```json
{
  "name": "lookup_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396329,
      "name": "lookup_address",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:615",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:protect_kernel_text_ro",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler",
        "arch/x86/mm/kmmio.c:get_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_page_list",
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387600,
      "name": "lookup_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t * lookup_address(long unsigned int address, unsigned int * level)
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
