# Function: <code>filemap_add_folio</code>

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
int filemap_add_folio(struct address_space * mapping, struct folio * folio, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "filemap_add_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935856,
      "name": "filemap_add_folio",
      "external": true,
      "loc": "mm/filemap.c:952",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935856,
      "name": "filemap_add_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int filemap_add_folio(struct address_space * mapping, struct folio * folio, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "filemap_add_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362928,
      "name": "filemap_add_folio",
      "external": true,
      "loc": "mm/filemap.c:928",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362928,
      "name": "filemap_add_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int filemap_add_folio(struct address_space * mapping, struct folio * folio, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "filemap_add_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566224,
      "name": "filemap_add_folio",
      "external": true,
      "loc": "mm/filemap.c:935",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566224,
      "name": "filemap_add_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int filemap_add_folio(struct address_space * mapping, struct folio * folio, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "filemap_add_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737072,
      "name": "filemap_add_folio",
      "external": true,
      "loc": "mm/filemap.c:931",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/folio-compat.c:add_to_page_cache_lru",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_order",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737072,
      "name": "filemap_add_folio",
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
int filemap_add_folio(struct address_space * mapping, struct folio * folio, long unsigned int index, gfp_t gfp)
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
