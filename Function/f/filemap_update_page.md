# Function: <code>filemap_update_page</code>

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
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, struct iov_iter * iter, struct page * page)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343040,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2365",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343040,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, struct iov_iter * iter, struct page * page)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590304,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2423",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590304,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, struct iov_iter * iter, struct folio * folio)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933616,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2463",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933616,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 693
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
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, struct iov_iter * iter, struct folio * folio)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370064,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2468",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370064,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, size_t count, struct folio * folio, bool need_uptodate)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574912,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2431",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574912,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, size_t count, struct folio * folio, bool need_uptodate)
```

```json
{
  "name": "filemap_update_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745040,
      "name": "filemap_update_page",
      "external": false,
      "loc": "mm/filemap.c:2366",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745040,
      "name": "filemap_update_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int filemap_update_page(struct kiocb * iocb, struct address_space * mapping, struct iov_iter * iter, struct page * page)
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
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param added. </b>
<code>bool need_uptodate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter * iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
