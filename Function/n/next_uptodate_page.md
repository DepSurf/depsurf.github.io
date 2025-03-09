# Function: <code>next_uptodate_page</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page * next_uptodate_page(struct page * page, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```

```json
{
  "name": "next_uptodate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327536,
      "name": "next_uptodate_page",
      "external": false,
      "loc": "mm/filemap.c:3116",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327536,
      "name": "next_uptodate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * next_uptodate_page(struct page * page, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```

```json
{
  "name": "next_uptodate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "next_uptodate_page",
      "external": false,
      "loc": "mm/filemap.c:3229",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575120,
      "name": "next_uptodate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
    },
    {
      "addr": 18446744071592189586,
      "name": "next_uptodate_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * next_uptodate_page(struct folio * folio, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```

```json
{
  "name": "next_uptodate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "next_uptodate_page",
      "external": false,
      "loc": "mm/filemap.c:3293",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930544,
      "name": "next_uptodate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    },
    {
      "addr": 18446744071593964542,
      "name": "next_uptodate_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * next_uptodate_page(struct folio * folio, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```

```json
{
  "name": "next_uptodate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "next_uptodate_page",
      "external": false,
      "loc": "mm/filemap.c:3300",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367184,
      "name": "next_uptodate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071596024040,
      "name": "next_uptodate_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
struct folio * next_uptodate_page(struct folio * folio, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```

```json
{
  "name": "next_uptodate_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "next_uptodate_page",
      "external": false,
      "loc": "mm/filemap.c:3439",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572720,
      "name": "next_uptodate_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071596546314,
      "name": "next_uptodate_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct page * next_uptodate_page(struct page * page, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```
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
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct folio * next_uptodate_page(struct folio * folio, struct address_space * mapping, struct xa_state * xas, long unsigned int end_pgoff)
```
</details>
</li>
</ul>
