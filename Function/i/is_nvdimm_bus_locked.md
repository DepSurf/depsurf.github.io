# Function: <code>is_nvdimm_bus_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584706912,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:49",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706912,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585054929,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052464,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585238209,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236288,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585320466,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317824,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585748383,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747040,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585994335,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993008,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586131183,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:50",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586129872,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586366146,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586364752,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586512944,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512944,
      "name": "is_nvdimm_bus_locked",
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
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294374,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587293056,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587354646,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353328,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587236486,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235456,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587802758,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587801728,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589152189,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150272,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590702605,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590700528,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591043677,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591041616,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591388188,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:43",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:alloc_nvdimm_map"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:dpa_align",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386080,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499395696,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499395696,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292634032,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292634032,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276627706,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276627706,
      "name": "is_nvdimm_bus_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586203424,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203424,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586021792,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021792,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586460912,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460912,
      "name": "is_nvdimm_bus_locked",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572608,
      "name": "is_nvdimm_bus_locked",
      "external": true,
      "loc": "drivers/nvdimm/core.c:42",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze",
        "drivers/nvdimm/dimm_devs.c:to_ndd",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_btt_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_pfn_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_dax_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572608,
      "name": "is_nvdimm_bus_locked",
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_nvdimm_bus_locked(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
