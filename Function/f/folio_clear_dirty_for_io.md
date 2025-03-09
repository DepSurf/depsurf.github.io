# Function: <code>folio_clear_dirty_for_io</code>

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
bool folio_clear_dirty_for_io(struct folio * folio)
```

```json
{
  "name": "folio_clear_dirty_for_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980928,
      "name": "folio_clear_dirty_for_io",
      "external": true,
      "loc": "mm/page-writeback.c:2801",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/vmscan.c:pageout",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/fuse/file.c:fuse_launder_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980928,
      "name": "folio_clear_dirty_for_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
bool folio_clear_dirty_for_io(struct folio * folio)
```

```json
{
  "name": "folio_clear_dirty_for_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417184,
      "name": "folio_clear_dirty_for_io",
      "external": true,
      "loc": "mm/page-writeback.c:2939",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:writeout",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/fuse/file.c:fuse_launder_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417184,
      "name": "folio_clear_dirty_for_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
bool folio_clear_dirty_for_io(struct folio * folio)
```

```json
{
  "name": "folio_clear_dirty_for_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621600,
      "name": "folio_clear_dirty_for_io",
      "external": true,
      "loc": "mm/page-writeback.c:2880",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:writeout",
        "fs/ext4/inode.c:mpage_submit_folio",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/fuse/file.c:fuse_launder_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621600,
      "name": "folio_clear_dirty_for_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
bool folio_clear_dirty_for_io(struct folio * folio)
```

```json
{
  "name": "folio_clear_dirty_for_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792800,
      "name": "folio_clear_dirty_for_io",
      "external": true,
      "loc": "mm/page-writeback.c:2859",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/folio-compat.c:clear_page_dirty_for_io",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:writeout",
        "fs/ext4/inode.c:mpage_submit_folio",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/fuse/file.c:fuse_launder_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792800,
      "name": "folio_clear_dirty_for_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
bool folio_clear_dirty_for_io(struct folio * folio)
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
