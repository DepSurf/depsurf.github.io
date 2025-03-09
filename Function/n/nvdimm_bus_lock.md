# Function: <code>nvdimm_bus_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584706816,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:29",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706816,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585052512,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_add_poison",
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052512,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236336,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_clear_from_poison_list",
        "drivers/nvdimm/core.c:nvdimm_bus_add_poison",
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236336,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317872,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317872,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585747088,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747088,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993056,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993056,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586129920,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:30",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586129920,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586364800,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586364800,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586512800,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512800,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294709,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292912,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355203,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353184,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587237043,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235312,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587803331,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587801584,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589152605,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:23",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150128,
      "name": "nvdimm_bus_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590703101,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:23",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590700336,
      "name": "nvdimm_bus_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591044173,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:23",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591041424,
      "name": "nvdimm_bus_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591388685,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:23",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:activate_store",
        "drivers/nvdimm/dimm_devs.c:activate_show",
        "drivers/nvdimm/dimm_devs.c:result_show",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:align_store",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:size_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591385888,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499395520,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499395520,
      "name": "nvdimm_bus_lock",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292633792,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292633792,
      "name": "nvdimm_bus_lock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276627536,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276627536,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586203280,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203280,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586021648,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021648,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586460768,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460768,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
```

```json
{
  "name": "nvdimm_bus_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572464,
      "name": "nvdimm_bus_lock",
      "external": true,
      "loc": "drivers/nvdimm/core.c:22",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nd_async_device_unregister",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:available_slots_show",
        "drivers/nvdimm/dimm_devs.c:state_show",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/nvdimm/dimm.c:nvdimm_remove",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/region_devs.c:dax_seed_show",
        "drivers/nvdimm/region_devs.c:pfn_seed_show",
        "drivers/nvdimm/region_devs.c:btt_seed_show",
        "drivers/nvdimm/region_devs.c:namespace_seed_show",
        "drivers/nvdimm/region_devs.c:init_namespaces_show",
        "drivers/nvdimm/region_devs.c:max_available_extent_show",
        "drivers/nvdimm/region_devs.c:available_size_show",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/region_devs.c:nd_region_activate",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:sector_size_store",
        "drivers/nvdimm/namespace_devs.c:uuid_store",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_capacity",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/claim.c:nd_detach_ndns",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:align_store",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572464,
      "name": "nvdimm_bus_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void nvdimm_bus_lock(struct device * dev)
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
