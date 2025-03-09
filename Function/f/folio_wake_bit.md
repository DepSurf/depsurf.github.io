# Function: <code>folio_wake_bit</code>

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
void folio_wake_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wake_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921856,
      "name": "folio_wake_bit",
      "external": false,
      "loc": "mm/filemap.c:1153",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921856,
      "name": "folio_wake_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void folio_wake_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wake_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358880,
      "name": "folio_wake_bit",
      "external": false,
      "loc": "mm/filemap.c:1129",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358880,
      "name": "folio_wake_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void folio_wake_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wake_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582561952,
      "name": "folio_wake_bit",
      "external": false,
      "loc": "mm/filemap.c:1138",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561952,
      "name": "folio_wake_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void folio_wake_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wake_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732736,
      "name": "folio_wake_bit",
      "external": false,
      "loc": "mm/filemap.c:1134",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_folio",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:folio_end_writeback",
        "mm/filemap.c:folio_end_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732736,
      "name": "folio_wake_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void folio_wake_bit(struct folio * folio, int bit_nr)
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
