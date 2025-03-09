# Function: <code>page_cache_async_ra</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_cache_async_ra(struct readahead_control * ractl, struct file_ra_state * ra, struct page * page, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581365936,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:581",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "fs/verity/enable.c:read_file_data_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365936,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_cache_async_ra(struct readahead_control * ractl, struct page * page, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581385408,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:582",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages",
        "fs/verity/enable.c:read_file_data_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385408,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_cache_async_ra(struct readahead_control * ractl, struct page * page, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581634512,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:584",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages",
        "fs/verity/enable.c:read_file_data_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634512,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_cache_async_ra(struct readahead_control * ractl, struct folio * folio, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000192,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:703",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages",
        "fs/verity/enable.c:read_file_data_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000192,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void page_cache_async_ra(struct readahead_control * ractl, struct folio * folio, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582436336,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:713",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages",
        "fs/verity/enable.c:build_merkle_tree_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436336,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void page_cache_async_ra(struct readahead_control * ractl, struct folio * folio, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582641744,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:712",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641744,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void page_cache_async_ra(struct readahead_control * ractl, struct folio * folio, long unsigned int req_count)
```

```json
{
  "name": "page_cache_async_ra",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582812848,
      "name": "page_cache_async_ra",
      "external": true,
      "loc": "mm/readahead.c:697",
      "file": "mm/readahead.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812848,
      "name": "page_cache_async_ra",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void page_cache_async_ra(struct readahead_control * ractl, struct file_ra_state * ra, struct page * page, long unsigned int req_count)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file_ra_state * ra</code>
</li>
<li>
<b>Param reordered. </b>
<code>ractl, ra, page, req_count</code> ➡️ <code>ractl, page, req_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
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
