# Function: <code>shmem_get_folio_gfp</code>

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
int shmem_get_folio_gfp(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_get_folio_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmem_get_folio_gfp",
      "external": false,
      "loc": "mm/shmem.c:1834",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567936,
      "name": "shmem_get_folio_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1937
    },
    {
      "addr": 18446744071596027387,
      "name": "shmem_get_folio_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int shmem_get_folio_gfp(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_get_folio_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmem_get_folio_gfp",
      "external": false,
      "loc": "mm/shmem.c:1857",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_folio_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_get_partial_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775136,
      "name": "shmem_get_folio_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2005
    },
    {
      "addr": 18446744071596549810,
      "name": "shmem_get_folio_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int shmem_get_folio_gfp(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp, gfp_t gfp, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_get_folio_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951328,
      "name": "shmem_get_folio_gfp",
      "external": false,
      "loc": "mm/shmem.c:1959",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_get_partial_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951328,
      "name": "shmem_get_folio_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
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
int shmem_get_folio_gfp(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, index, foliop, sgp, gfp, vma, vmf, fault_type</code> ➡️ <code>inode, index, foliop, sgp, gfp, vmf, fault_type</code>
</li>
</ul>
</details>
</li>
</ul>
