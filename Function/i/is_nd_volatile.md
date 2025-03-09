# Function: <code>is_nd_volatile</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585338781,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:171",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
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
      "addr": 18446744071585340896,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585767216,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:171",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
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
      "addr": 18446744071585769280,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586013333,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:171",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071586015728,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151861,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:176",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071586154448,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586387119,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071586389648,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530901,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446744071586537472,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312277,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:852",
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
      "addr": 18446744071587322128,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587374245,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:852",
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
      "addr": 18446744071587384064,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587256277,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:859",
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
      "addr": 18446744071587266192,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587823349,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:859",
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
      "addr": 18446744071587833392,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589173541,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:802",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:is_nvdimm_sync",
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
      "addr": 18446744071589185536,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590726229,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:847",
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
      "addr": 18446744071590739520,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(const struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591067557,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:847",
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
      "addr": 18446744071591080880,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(const struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591412293,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:848",
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
      "addr": 18446744071591425776,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499417632,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446603336499426176,
      "name": "is_nd_volatile",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292661584,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 13835058055292670736,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276645806,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446743936276653058,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586221381,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446744071586227952,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586039749,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446744071586046320,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586478869,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446744071586485440,
      "name": "is_nd_volatile",
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
bool is_nd_volatile(struct device * dev)
```

```json
{
  "name": "is_nd_volatile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590485,
      "name": "is_nd_volatile",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:168",
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
      "addr": 18446744071586597184,
      "name": "is_nd_volatile",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool is_nd_volatile(struct device * dev)
```
</details>
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
bool is_nd_volatile(struct device * dev)
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
