# Function: <code>is_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_memory(struct acpi_resource * res, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583594292,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:259",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583594292,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int is_memory(struct acpi_resource * res, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916871,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:291",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916871,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int is_memory(struct acpi_resource * res, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057767,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:302",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057767,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * res, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119024,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:346",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585318987,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585323188,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585329510,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585338603,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585361675,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585379989,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384429,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:73",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119024,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360800,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:639",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584390512,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:346",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585751156,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585757398,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585766859,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585786869,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585801227,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585809413,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585813629,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360800,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071584390512,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581808,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:639",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612048,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:353",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585997124,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586003477,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013307,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
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
      "caller_func": []
    },
    {
      "addr": 18446744071586032843,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047365,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586055653,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586059909,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:72",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581808,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071584612048,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584679200,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:639",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584709648,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586134436,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586140501,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586151835,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
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
      "caller_func": []
    },
    {
      "addr": 18446744071586172042,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187589,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195892,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586200789,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:128",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679200,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071584709648,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584879344,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584910768,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:374",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586368774,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586376197,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586387093,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
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
      "caller_func": []
    },
    {
      "addr": 18446744071586410182,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586424757,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433107,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586437397,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:122",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879344,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584910768,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585015216,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585046480,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586518005,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586524357,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586534853,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071586540415,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586557029,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571397,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579780,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586584389,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015216,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585046480,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715216,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585749472,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:370",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587297109,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587305973,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313125,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587324271,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342625,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356741,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364933,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369941,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715216,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585749472,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585837328,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:624",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585868560,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587358370,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587366903,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375061,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587386111,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587404353,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418062,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426165,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430638,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837328,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585868560,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585716592,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:669",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585746336,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587240850,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587248852,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257911,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268239,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587286097,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299936,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587308069,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587312510,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716592,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585746336,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586197920,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:676",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586228880,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:376",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587806978,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587817684,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828183,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587835471,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587852732,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587866752,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587874869,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879374,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:110",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197920,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071586228880,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587434832,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:676",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587467168,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:395",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589178928,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589186879,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589216187,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224692,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229533,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434832,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071587467168,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588692496,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:793",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590732320,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590741023,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590771883,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590781076,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786541,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692496,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588980384,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:834",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591073648,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591082383,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591113291,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591122580,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591128045,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980384,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284144,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:897",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591418544,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:size_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591427279,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591458619,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591468052,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591473725,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:92",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284144,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497426432,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499401628,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499409964,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499423096,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446603336499429516,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499446696,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499461036,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511288132,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/firmware/efi/arm-init.c:26",
      "file": "drivers/firmware/efi/arm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-init.c:reserve_regions"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497426432,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "is_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243940772,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/firmware/efi/arm-init.c:26",
      "file": "drivers/firmware/efi/arm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-init.c:reserve_regions"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292640848,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292652444,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292667036,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 13835058055292675264,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292704928,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292725000,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292738096,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292744016,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "is_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276633226,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276639208,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276650702,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446743936276655276,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276670174,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276682656,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584958576,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586208485,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586214837,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586225333,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071586230895,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586247509,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586261877,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270260,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274869,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958576,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584867376,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584893504,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586026853,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586033205,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586043701,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071586049263,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065877,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080245,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586088628,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586093237,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867376,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584893504,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584966800,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584998064,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586465973,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586472325,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586482821,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071586488383,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504997,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519365,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586527748,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586532357,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966800,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584998064,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```

```json
{
  "name": "is_memory",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072976,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/resource.c:631",
      "file": "drivers/acpi/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585104240,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:377",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586577653,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586584005,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586594565,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071586600127,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586616741,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631333,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586639476,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586644085,
      "name": "is_memory",
      "external": false,
      "loc": "drivers/nvdimm/nd-core.h:109",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072976,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585104240,
      "name": "is_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_resource * ares</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_resource * res</code>
</li>
</ul>
</details>
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
int is_memory(struct acpi_resource * ares, void * not_used)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int is_memory(struct acpi_resource * ares, void * not_used)
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
