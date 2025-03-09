# Function: <code>sizeof_namespace_label</code>

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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372043,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364368,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799785,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791072,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586041670,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037600,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586181782,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176848,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586418750,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586413648,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586565518,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560288,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587350183,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344720,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587411703,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406256,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587293716,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288208,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587860468,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nsl_validate_blk_isetcookie",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid",
        "drivers/nvdimm/label.c:reap_victim",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854992,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589212015,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:45",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206080,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590767567,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:45",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761600,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591109002,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:45",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591103040,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591454330,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:45",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448320,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499455600,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499449872,
      "name": "sizeof_namespace_label",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292716440,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292708784,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276677894,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276673054,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255998,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250768,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586074366,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069136,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586513486,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508256,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "sizeof_namespace_label",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586625230,
      "name": "sizeof_namespace_label",
      "external": true,
      "loc": "drivers/nvdimm/label.c:37",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
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
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:__nd_label_validate",
        "drivers/nvdimm/label.c:sizeof_namespace_index"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620000,
      "name": "sizeof_namespace_label",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
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
unsigned int sizeof_namespace_label(struct nvdimm_drvdata * ndd)
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
