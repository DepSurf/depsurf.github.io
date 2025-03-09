# Function: <code>radix_tree_next_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_next_chunk(struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967024,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:752",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_tag",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_pages",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/backing-dev.c:bdi_unregister",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/radix-tree.c:radix_tree_gang_lookup",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967024,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void * * radix_tree_next_chunk(struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253632,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:913",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages",
        "mm/filemap.c:find_get_entries",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/backing-dev.c:bdi_unregister",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253632,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
void * * radix_tree_next_chunk(struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369712,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1571",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages",
        "mm/filemap.c:find_get_entries",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/backing-dev.c:bdi_unregister",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369712,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
void * * radix_tree_next_chunk(const struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218416,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1714",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages",
        "mm/filemap.c:find_get_entries",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/backing-dev.c:bdi_unregister",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_remove",
        "lib/idr.c:idr_get_next",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218416,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
void * * radix_tree_next_chunk(const struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588768384,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/backing-dev.c:bdi_unregister",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_remove",
        "lib/idr.c:idr_get_next_ext",
        "lib/idr.c:idr_get_next",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768384,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
void * * radix_tree_next_chunk(const struct radix_tree_root * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589147184,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1711",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/backing-dev.c:bdi_unregister",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_remove",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_get_next",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589147184,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381168,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1176",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_get_next",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381168,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589838480,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_get_next",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838480,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590064576,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064576,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063840,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1155",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063840,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585213136,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1155",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213136,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095616,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1156",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095616,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1156",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342882,
      "name": "radix_tree_next_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071585543376,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1156",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594204450,
      "name": "radix_tree_next_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071586698672,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1156",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373649,
      "name": "radix_tree_next_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071595859184,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 990
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1154",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903275,
      "name": "radix_tree_next_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071596376256,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1121
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1154",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597828368,
      "name": "radix_tree_next_chunk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071597271504,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1121
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503842880,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503842880,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236462132,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236462132,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297695424,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297695424,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279732434,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "drivers/pinctrl/pinmux.c:pinmux_generic_free_functions",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279732434,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666832,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666832,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589392656,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392656,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590110208,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590110208,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void * * radix_tree_next_chunk(const struct xarray * root, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "radix_tree_next_chunk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590160544,
      "name": "radix_tree_next_chunk",
      "external": true,
      "loc": "lib/radix-tree.c:1163",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "lib/idr.c:idr_get_next_ul",
        "lib/idr.c:idr_for_each",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag_slot",
        "lib/radix-tree.c:radix_tree_gang_lookup_tag",
        "lib/radix-tree.c:radix_tree_gang_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590160544,
      "name": "radix_tree_next_chunk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
