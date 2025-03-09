# Function: <code>filemap_get_folios</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int filemap_get_folios(struct address_space * mapping, long unsigned int * start, long unsigned int end, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_folios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_folios",
      "external": true,
      "loc": "mm/filemap.c:2163",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023922,
      "name": "filemap_get_folios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582365712,
      "name": "filemap_get_folios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
unsigned int filemap_get_folios(struct address_space * mapping, long unsigned int * start, long unsigned int end, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_folios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_folios",
      "external": true,
      "loc": "mm/filemap.c:2134",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596546170,
      "name": "filemap_get_folios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582570096,
      "name": "filemap_get_folios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
unsigned int filemap_get_folios(struct address_space * mapping, long unsigned int * start, long unsigned int end, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_folios",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741728,
      "name": "filemap_get_folios",
      "external": true,
      "loc": "mm/filemap.c:2113",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unlock_mapping",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741728,
      "name": "filemap_get_folios",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int filemap_get_folios(struct address_space * mapping, long unsigned int * start, long unsigned int end, struct folio_batch * fbatch)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
