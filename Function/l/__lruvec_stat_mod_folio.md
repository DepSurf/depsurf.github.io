# Function: <code>__lruvec_stat_mod_folio</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lruvec_stat_mod_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581935107,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987495,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087968,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
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
  "name": "__lruvec_stat_mod_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582362563,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:606",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415127,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:606",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582559212,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:606",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009785,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:606",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309724,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:606",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__lruvec_stat_mod_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582565863,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582621111,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765330,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583091118,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218107,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583529187,
      "name": "__lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:612",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __lruvec_stat_mod_folio(struct folio * folio, enum node_stat_item idx, int val)
```

```json
{
  "name": "__lruvec_stat_mod_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583804992,
      "name": "__lruvec_stat_mod_folio",
      "external": true,
      "loc": "mm/memcontrol.c:899",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:lruvec_stat_mod_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:folio_remove_rmap_pmd",
        "mm/rmap.c:folio_remove_rmap_pmd",
        "mm/rmap.c:folio_remove_rmap_ptes",
        "mm/rmap.c:folio_add_file_rmap_pmd",
        "mm/rmap.c:folio_add_file_rmap_pmd",
        "mm/rmap.c:folio_add_file_rmap_ptes",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:folio_add_anon_rmap_pmd",
        "mm/rmap.c:folio_add_anon_rmap_pmd",
        "mm/rmap.c:folio_add_anon_rmap_pmd",
        "mm/rmap.c:folio_add_anon_rmap_ptes",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804992,
      "name": "__lruvec_stat_mod_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void __lruvec_stat_mod_folio(struct folio * folio, enum node_stat_item idx, int val)
```
</details>
</li>
</ul>
