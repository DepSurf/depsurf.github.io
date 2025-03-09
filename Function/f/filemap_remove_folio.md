# Function: <code>filemap_remove_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void filemap_remove_folio(struct folio * folio)
```

```json
{
  "name": "filemap_remove_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946192,
      "name": "filemap_remove_folio",
      "external": true,
      "loc": "mm/filemap.c:248",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:delete_from_page_cache",
        "mm/folio-compat.c:delete_from_page_cache",
        "mm/readahead.c:read_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/shmem.c:shmem_getpage_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946192,
      "name": "filemap_remove_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void filemap_remove_folio(struct folio * folio)
```

```json
{
  "name": "filemap_remove_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379952,
      "name": "filemap_remove_folio",
      "external": true,
      "loc": "mm/filemap.c:248",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:read_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379952,
      "name": "filemap_remove_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void filemap_remove_folio(struct folio * folio)
```

```json
{
  "name": "filemap_remove_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580928,
      "name": "filemap_remove_folio",
      "external": true,
      "loc": "mm/filemap.c:253",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:read_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580928,
      "name": "filemap_remove_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void filemap_remove_folio(struct folio * folio)
```

```json
{
  "name": "filemap_remove_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751488,
      "name": "filemap_remove_folio",
      "external": true,
      "loc": "mm/filemap.c:248",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:read_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_folio",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751488,
      "name": "filemap_remove_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void filemap_remove_folio(struct folio * folio)
```
</details>
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
