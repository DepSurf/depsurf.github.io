# Function: <code>to_nd_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584716832,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:69",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:available_size_show"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716832,
      "name": "to_nd_region.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584716864,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585068117,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:157",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068032,
      "name": "to_nd_region.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585068064,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585252901,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:172",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:blk_dpa_busy",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585252816,
      "name": "to_nd_region.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585252848,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337461,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:176",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585334848,
      "name": "to_nd_region.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585334864,
      "name": "to_nd_region",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585765541,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:176",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585762928,
      "name": "to_nd_region.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585762944,
      "name": "to_nd_region",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586011957,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:176",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009344,
      "name": "to_nd_region.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586009360,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147909,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:181",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147840,
      "name": "to_nd_region.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586147856,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586383493,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392286,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586392311,
      "name": "to_nd_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586383440,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586531141,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586531072,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586531088,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587314677,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:143",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_detach_and_reset",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587314640,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587376613,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:143",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_detach_and_reset",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376576,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587258309,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:143",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587258272,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587833946,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:143",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_release",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823424,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589173685,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:140",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173632,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590726405,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:187",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590726336,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591067733,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:187",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067664,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591412469,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:188",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mapping31_show",
        "drivers/nvdimm/region_devs.c:mapping30_show",
        "drivers/nvdimm/region_devs.c:mapping29_show",
        "drivers/nvdimm/region_devs.c:mapping28_show",
        "drivers/nvdimm/region_devs.c:mapping27_show",
        "drivers/nvdimm/region_devs.c:mapping26_show",
        "drivers/nvdimm/region_devs.c:mapping25_show",
        "drivers/nvdimm/region_devs.c:mapping24_show",
        "drivers/nvdimm/region_devs.c:mapping23_show",
        "drivers/nvdimm/region_devs.c:mapping22_show",
        "drivers/nvdimm/region_devs.c:mapping21_show",
        "drivers/nvdimm/region_devs.c:mapping20_show",
        "drivers/nvdimm/region_devs.c:mapping19_show",
        "drivers/nvdimm/region_devs.c:mapping18_show",
        "drivers/nvdimm/region_devs.c:mapping17_show",
        "drivers/nvdimm/region_devs.c:mapping16_show",
        "drivers/nvdimm/region_devs.c:mapping15_show",
        "drivers/nvdimm/region_devs.c:mapping14_show",
        "drivers/nvdimm/region_devs.c:mapping13_show",
        "drivers/nvdimm/region_devs.c:mapping12_show",
        "drivers/nvdimm/region_devs.c:mapping11_show",
        "drivers/nvdimm/region_devs.c:mapping10_show",
        "drivers/nvdimm/region_devs.c:mapping9_show",
        "drivers/nvdimm/region_devs.c:mapping8_show",
        "drivers/nvdimm/region_devs.c:mapping7_show",
        "drivers/nvdimm/region_devs.c:mapping6_show",
        "drivers/nvdimm/region_devs.c:mapping5_show",
        "drivers/nvdimm/region_devs.c:mapping4_show",
        "drivers/nvdimm/region_devs.c:mapping3_show",
        "drivers/nvdimm/region_devs.c:mapping2_show",
        "drivers/nvdimm/region_devs.c:mapping1_show",
        "drivers/nvdimm/region_devs.c:mapping0_show",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:persistence_domain_show",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:align_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_init",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412400,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499418020,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499417864,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336499417896,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292661664,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292661664,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276646358,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276646230,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936276646258,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586221621,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221552,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586221568,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586039989,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable",
        "drivers/acpi/nfit/core.c:range_index_show",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/nvdimm/pmem.c:nd_pmem_shutdown",
        "drivers/nvdimm/pmem.c:nd_pmem_remove",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/pmem.c:pmem_make_request",
        "drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt",
        "drivers/dax/pmem/core.c:__dax_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039920,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586039936,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586479109,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479040,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586479056,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_region * to_nd_region(struct device * dev)
```

```json
{
  "name": "to_nd_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590853,
      "name": "to_nd_region",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:173",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:mapping_visible",
        "drivers/nvdimm/region_devs.c:mappingN",
        "drivers/nvdimm/region_devs.c:region_visible",
        "drivers/nvdimm/region_devs.c:resource_show",
        "drivers/nvdimm/region_devs.c:region_badblocks_show",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:read_only_show",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nstype_show",
        "drivers/nvdimm/region_devs.c:mappings_show",
        "drivers/nvdimm/region_devs.c:deep_flush_show",
        "drivers/nvdimm/region_devs.c:size_show",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region.c:nd_region_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_locked",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nstype_show",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:namespace_blk_release",
        "drivers/nvdimm/namespace_devs.c:namespace_pmem_release",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/claim.c:nsio_rw_bytes",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590784,
      "name": "to_nd_region.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586590800,
      "name": "to_nd_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nd_region * to_nd_region(struct device * dev)
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
