# Function: <code>clflush_cache_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287984,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:130",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "drivers/iommu/dmar.c:qi_submit_sync",
        "drivers/iommu/dmar.c:qi_submit_sync",
        "drivers/iommu/dmar.c:qi_submit_sync",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287984,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287584,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:134",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287584,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302976,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:134",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel_irq_remapping.c:modify_irte",
        "drivers/nvdimm/claim.c:nsio_rw_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302976,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300704,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:135",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300704,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322112,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:135",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush_range",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem",
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322112,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579332976,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:153",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush_range",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem",
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332976,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359445,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:298",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359408,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374037,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374000,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579378293,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378224,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417909,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:306",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417840,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417941,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:306",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417872,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420965,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:314",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421024,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484549,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:314",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484608,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564309,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:317",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564224,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672341,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:335",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr",
        "drivers/iommu/intel/iommu.c:iommu_context_addr",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672240,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686245,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:336",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr",
        "drivers/iommu/intel/iommu.c:iommu_context_addr",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686144,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720773,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:336",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel/iommu.c:dma_pte_free_level",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720672,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374197,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374128,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304389,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304320,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579374117,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374048,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382597,
      "name": "clflush_cache_range",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:299",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc",
        "drivers/iommu/intel-iommu.c:domain_context_clear_one_cb",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_level",
        "drivers/iommu/intel-iommu.c:dma_pte_free_level",
        "drivers/iommu/intel-iommu.c:dma_pte_clear_range",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382528,
      "name": "clflush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void clflush_cache_range(void * vaddr, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clflush_cache_range(void * vaddr, unsigned int size)
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
