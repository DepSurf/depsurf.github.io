# Function: <code>to_ndd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584712048,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:221",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/label.c:del_label",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712048,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062960,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:221",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:del_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062960,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585246800,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585246800,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329264,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:246",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329264,
      "name": "to_ndd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585757152,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:253",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585757152,
      "name": "to_ndd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586003248,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:255",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003248,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586140240,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:243",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140240,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375936,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375936,
      "name": "to_ndd",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586523984,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523984,
      "name": "to_ndd",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587310181,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:add_namespace_resource",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:init_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304832,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587372213,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:add_namespace_resource",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:init_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365920,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587254229,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:add_namespace_resource",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587247872,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587821381,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:230",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:add_namespace_resource",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814560,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589170133,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:210",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589163552,
      "name": "to_ndd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590722421,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:210",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715312,
      "name": "to_ndd",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591063653,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:210",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591056528,
      "name": "to_ndd",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591408405,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:212",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:init_active_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591401232,
      "name": "to_ndd",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499409480,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499409480,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292650672,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292650672,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276638760,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276638760,
      "name": "to_ndd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214464,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214464,
      "name": "to_ndd",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032832,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032832,
      "name": "to_ndd",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586471952,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471952,
      "name": "to_ndd",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
```

```json
{
  "name": "to_ndd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586583632,
      "name": "to_ndd",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:240",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:alias_dpa_busy",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:release_free_pmem",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/label.c:nd_blk_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583632,
      "name": "to_ndd",
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
struct nvdimm_drvdata * to_ndd(struct nd_mapping * nd_mapping)
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
