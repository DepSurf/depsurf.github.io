# Function: <code>preamble_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool preamble_index(struct nvdimm_drvdata * ndd, int idx, struct nd_namespace_index * * nsindex_out, long unsigned int * * free, u32 * nslot)
```

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737952,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:229",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737952,
      "name": "preamble_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
bool preamble_index(struct nvdimm_drvdata * ndd, int idx, struct nd_namespace_index * * nsindex_out, long unsigned int * * free, u32 * nslot)
```

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585090320,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:229",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090320,
      "name": "preamble_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
bool preamble_index(struct nvdimm_drvdata * ndd, int idx, struct nd_namespace_index * * nsindex_out, long unsigned int * * free, u32 * nslot)
```

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585277840,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:229",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277840,
      "name": "preamble_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585371864,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:294",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362816,
      "name": "preamble_index.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799606,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:296",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791216,
      "name": "preamble_index.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586041478,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:305",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586181590,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:313",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586418547,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586565315,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587349955,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587411475,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587293491,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587860243,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589211745,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:315",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590767297,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:315",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591108729,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:315",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591454057,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:315",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499455280,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292716168,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276677744,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586255795,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586074163,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586513283,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "preamble_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586625027,
      "name": "preamble_index",
      "external": false,
      "loc": "drivers/nvdimm/label.c:307",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_nfree",
        "drivers/nvdimm/label.c:nd_label_free_slot",
        "drivers/nvdimm/label.c:nd_label_alloc_slot",
        "drivers/nvdimm/label.c:nd_label_active",
        "drivers/nvdimm/label.c:nd_label_active_count",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool preamble_index(struct nvdimm_drvdata * ndd, int idx, struct nd_namespace_index * * nsindex_out, long unsigned int * * free, u32 * nslot)
```
</details>
</li>
</ul>
