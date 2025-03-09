# Function: <code>is_nd_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584718895,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:59",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721280,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585070994,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:147",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/bus.c:pmem_active",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073504,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585255794,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:162",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/bus.c:pmem_active",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:blk_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257760,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334728,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:161",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nvdimm_has_cache",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340832,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585762808,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:161",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nvdimm_has_cache",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769216,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586013307,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:161",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015664,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151835,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:166",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154384,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586383301,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389584,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530930,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537408,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312306,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:842",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322064,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587374274,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:842",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384000,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587256306,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:849",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266128,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587823378,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:849",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833328,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589173570,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:797",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:nvdimm_has_cache",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589185488,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590726258,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:842",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590739456,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pmem(const struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591067586,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:842",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591080816,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pmem(const struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591412322,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:843",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591425712,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499417660,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499426032,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292661616,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292670576,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276645824,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276652954,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586221410,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227888,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586039778,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046256,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586478898,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485376,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool is_nd_pmem(struct device * dev)
```

```json
{
  "name": "is_nd_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590514,
      "name": "is_nd_pmem",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:158",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586597120,
      "name": "is_nd_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device * dev</code> ➡️ <code>const struct device * dev</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_nd_pmem(struct device * dev)
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
