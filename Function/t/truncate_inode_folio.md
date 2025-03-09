# Function: <code>truncate_inode_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int truncate_inode_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "truncate_inode_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582025779,
      "name": "truncate_inode_folio",
      "external": true,
      "loc": "mm/truncate.c:190",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023968,
      "name": "truncate_inode_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int truncate_inode_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "truncate_inode_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582459669,
      "name": "truncate_inode_folio",
      "external": true,
      "loc": "mm/truncate.c:190",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458080,
      "name": "truncate_inode_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int truncate_inode_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "truncate_inode_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582664774,
      "name": "truncate_inode_folio",
      "external": true,
      "loc": "mm/truncate.c:190",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_page",
        "mm/truncate.c:truncate_inode_partial_folio"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663312,
      "name": "truncate_inode_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int truncate_inode_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "truncate_inode_folio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582835617,
      "name": "truncate_inode_folio",
      "external": true,
      "loc": "mm/truncate.c:189",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:generic_error_remove_folio",
        "mm/truncate.c:truncate_inode_partial_folio"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834128,
      "name": "truncate_inode_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int truncate_inode_folio(struct address_space * mapping, struct folio * folio)
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
