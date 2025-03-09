# Function: <code>folio_invalidate</code>

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
void folio_invalidate(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "folio_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024525,
      "name": "folio_invalidate",
      "external": true,
      "loc": "mm/truncate.c:154",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020576,
      "name": "folio_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void folio_invalidate(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "folio_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582458487,
      "name": "folio_invalidate",
      "external": true,
      "loc": "mm/truncate.c:154",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454384,
      "name": "folio_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void folio_invalidate(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "folio_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582663704,
      "name": "folio_invalidate",
      "external": true,
      "loc": "mm/truncate.c:154",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659648,
      "name": "folio_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void folio_invalidate(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "folio_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582834539,
      "name": "folio_invalidate",
      "external": true,
      "loc": "mm/truncate.c:153",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830768,
      "name": "folio_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void folio_invalidate(struct folio * folio, size_t offset, size_t length)
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
