# Function: <code>shmem_get_folio</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_get_folio(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp)
```

```json
{
  "name": "shmem_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582570915,
      "name": "shmem_get_folio",
      "external": true,
      "loc": "mm/shmem.c:2048",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mcopy_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581328,
      "name": "shmem_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int shmem_get_folio(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp)
```

```json
{
  "name": "shmem_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582784307,
      "name": "shmem_get_folio",
      "external": true,
      "loc": "mm/shmem.c:2078",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_get_partial_folio"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mfill_atomic_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788528,
      "name": "shmem_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int shmem_get_folio(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp)
```

```json
{
  "name": "shmem_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582959795,
      "name": "shmem_get_folio",
      "external": true,
      "loc": "mm/shmem.c:2131",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_get_partial_folio"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mfill_atomic_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963792,
      "name": "shmem_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int shmem_get_folio(struct inode * inode, long unsigned int index, struct folio * * foliop, enum sgp_type sgp)
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
