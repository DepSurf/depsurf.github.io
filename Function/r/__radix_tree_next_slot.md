# Function: <code>__radix_tree_next_slot</code>

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
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "__radix_tree_next_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368160,
      "name": "__radix_tree_next_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1488",
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
      "addr": 18446744071583368160,
      "name": "__radix_tree_next_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "__radix_tree_next_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217136,
      "name": "__radix_tree_next_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1631",
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
        "lib/idr.c:ida_get_new_above",
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
      "addr": 18446744071588217136,
      "name": "__radix_tree_next_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "__radix_tree_next_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767104,
      "name": "__radix_tree_next_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1629",
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
        "lib/idr.c:ida_get_new_above",
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
      "addr": 18446744071588767104,
      "name": "__radix_tree_next_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```

```json
{
  "name": "__radix_tree_next_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589146240,
      "name": "__radix_tree_next_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1628",
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
        "lib/idr.c:ida_get_new_above",
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
      "addr": 18446744071589146240,
      "name": "__radix_tree_next_slot",
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void * * __radix_tree_next_slot(void * * slot, struct radix_tree_iter * iter, unsigned int flags)
```
</details>
</li>
</ul>
