# Function: <code>sizeof_namespace_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584737696,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:preamble_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737696,
      "name": "sizeof_namespace_index.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584739440,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585097684,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:preamble_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/dimm.c:nvdimm_probe",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090064,
      "name": "sizeof_namespace_index.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585091744,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585285952,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:preamble_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277664,
      "name": "sizeof_namespace_index.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585279328,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372275,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:48",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362688,
      "name": "sizeof_namespace_index.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585364384,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585791120,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791120,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037680,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:71",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037680,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176928,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:71",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176928,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586424251,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586413728,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571051,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586560368,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587349382,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355851,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587344800,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587410902,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591517359,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587406336,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587292908,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591459336,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587288288,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587859678,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592522534,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587855072,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589211113,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:73",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_copy",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594392971,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589206192,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590766529,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:73",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_copy",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761744,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591107953,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:73",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_copy",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591103184,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591453281,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:73",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_copy",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448464,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499449992,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499449992,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292708864,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292708864,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276673162,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276673162,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261531,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586250848,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079899,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586069216,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519019,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586508336,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sizeof_namespace_index",
      "external": true,
      "loc": "drivers/nvdimm/label.c:65",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:set_cookie_show",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:holder_class_store",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:nd_label_base",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630763,
      "name": "sizeof_namespace_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586620080,
      "name": "sizeof_namespace_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
size_t sizeof_namespace_index(struct nvdimm_drvdata * ndd)
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
