# Function: <code>__radix_tree_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __radix_tree_lookup(struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969616,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:491",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "lib/radix-tree.c:radix_tree_lookup_slot",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_delete_item"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969616,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void * __radix_tree_lookup(struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258240,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:677",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:get_unlocked_mapping_entry",
        "lib/radix-tree.c:radix_tree_replace_clear_tags",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258240,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void * __radix_tree_lookup(struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374880,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:911",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_invalidate_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:get_unlocked_mapping_entry",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374880,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void * __radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224240,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:get_unlocked_mapping_entry",
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224240,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void * __radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774304,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1028",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry",
        "fs/dax.c:get_unlocked_mapping_entry",
        "lib/idr.c:idr_replace_ext",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774304,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void * __radix_tree_lookup(const struct radix_tree_root * root, long unsigned int index, struct radix_tree_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153008,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:1029",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_radix_tree_replace",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:unlock_mapping_entry",
        "fs/dax.c:__get_unlocked_mapping_entry",
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_split",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153008,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385632,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:769",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385632,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589842656,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589842656,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068752,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068752,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065872,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065872,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215200,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215200,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098048,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098048,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343810,
      "name": "__radix_tree_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585546272,
      "name": "__radix_tree_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205330,
      "name": "__radix_tree_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586701920,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:748",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374543,
      "name": "__radix_tree_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071595863600,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:747",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596904063,
      "name": "__radix_tree_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071596380960,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:747",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829156,
      "name": "__radix_tree_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071597276208,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503846680,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503846680,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236466184,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236466184,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297700656,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297700656,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279736732,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279736732,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671008,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671008,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396832,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589396832,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114384,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590114384,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void * __radix_tree_lookup(const struct xarray * root, long unsigned int index, struct xa_node * * nodep, void * * * slotp)
```

```json
{
  "name": "__radix_tree_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164768,
      "name": "__radix_tree_lookup",
      "external": true,
      "loc": "lib/radix-tree.c:756",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/idr.c:idr_replace",
        "lib/radix-tree.c:radix_tree_delete_item",
        "lib/radix-tree.c:radix_tree_lookup",
        "lib/radix-tree.c:radix_tree_lookup_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164768,
      "name": "__radix_tree_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>const struct radix_tree_root * root</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct radix_tree_root * root</code> ➡️ <code>const struct xarray * root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node * * nodep</code> ➡️ <code>struct xa_node * * nodep</code>
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
