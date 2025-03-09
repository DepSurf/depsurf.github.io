# Function: <code>__radix_tree_replace</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __radix_tree_replace(struct radix_tree_root * root, struct radix_tree_node * node, void * * slot, void * item, radix_tree_update_node_t update_node, void * private)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375216,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1060",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375216,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void __radix_tree_replace(struct radix_tree_root * root, struct radix_tree_node * node, void * * slot, void * item, radix_tree_update_node_t update_node, void * private)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224832,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1181",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_radix_tree_replace",
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224832,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void __radix_tree_replace(struct radix_tree_root * root, struct radix_tree_node * node, void * * slot, void * item, radix_tree_update_node_t update_node)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774896,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1179",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "lib/idr.c:idr_replace_ext",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774896,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void __radix_tree_replace(struct radix_tree_root * root, struct radix_tree_node * node, void * * slot, void * item, radix_tree_update_node_t update_node)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153552,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:1180",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153552,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386096,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:897",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386096,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843120,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843120,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069216,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069216,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585065792,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066368,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585215120,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215696,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585097968,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098544,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585545040,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546800,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586700592,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702544,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595862176,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:876",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595864304,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596379408,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:875",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596381648,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597274656,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:875",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_slot"
      ],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597276896,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503847184,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503847184,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236466744,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236466744,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297701312,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297701312,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279737148,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279737148,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671472,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671472,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397296,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397296,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114848,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590114848,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __radix_tree_replace(struct xarray * root, struct xa_node * node, void * * slot, void * item)
```

```json
{
  "name": "__radix_tree_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165232,
      "name": "__radix_tree_replace",
      "external": true,
      "loc": "lib/radix-tree.c:884",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_iter_replace",
        "lib/radix-tree.c:radix_tree_replace_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165232,
      "name": "__radix_tree_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __radix_tree_replace(struct radix_tree_root * root, struct radix_tree_node * node, void * * slot, void * item, radix_tree_update_node_t update_node, void * private)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * private</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>radix_tree_update_node_t update_node</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node * node</code> ➡️ <code>struct xa_node * node</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
