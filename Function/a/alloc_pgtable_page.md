# Function: <code>alloc_pgtable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584307168,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:645",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307168,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584666377,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:652",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653376,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595711424,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:653",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
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
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596636290,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:658",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
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
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602966371,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:631",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
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
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603137655,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:633",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585727072,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:509",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727072,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585956864,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:503",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956864,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100144,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:514",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100144,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609374814,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:511",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855856,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612446074,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:501",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908912,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614586639,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:510",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788736,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587341191,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:499",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587345312,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588658537,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:399",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:copy_context_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659472,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * alloc_pgtable_page()
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590097159,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable_v2.c:49",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131077,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:374",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132704,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * alloc_pgtable_page(int nid, gfp_t gfp)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590407280,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/amd_iommu.h:126",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590410968,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/amd_iommu.h:126",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590441120,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:374",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590441120,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * alloc_pgtable_page(int nid, gfp_t gfp)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590737235,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/amd_iommu.h:145",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590751302,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/amd_iommu.h:145",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590755080,
      "name": "alloc_pgtable_page",
      "external": false,
      "loc": "drivers/iommu/amd/amd_iommu.h:145",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590787472,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:237",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590787472,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585860832,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:514",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860832,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720288,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:514",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720288,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586050160,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:514",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050160,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * alloc_pgtable_page(int node)
```

```json
{
  "name": "alloc_pgtable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586158208,
      "name": "alloc_pgtable_page",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:514",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_context_addr",
        "drivers/iommu/intel-pasid.c:intel_pasid_get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158208,
      "name": "alloc_pgtable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void * alloc_pgtable_page(int node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * alloc_pgtable_page(int node)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
void * alloc_pgtable_page(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * alloc_pgtable_page(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * alloc_pgtable_page(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * alloc_pgtable_page(int node)
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
