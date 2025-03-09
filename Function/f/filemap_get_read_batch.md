# Function: <code>filemap_get_read_batch</code>

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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct pagevec * pvec)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581333328,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2278",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333328,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct pagevec * pvec)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2332",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577504,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    },
    {
      "addr": 18446744071592189676,
      "name": "filemap_get_read_batch.cold",
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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2376",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936032,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    },
    {
      "addr": 18446744071593964751,
      "name": "filemap_get_read_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2373",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371184,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    },
    {
      "addr": 18446744071596024124,
      "name": "filemap_get_read_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2338",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576032,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071596546360,
      "name": "filemap_get_read_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct folio_batch * fbatch)
```

```json
{
  "name": "filemap_get_read_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_get_read_batch",
      "external": false,
      "loc": "mm/filemap.c:2273",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745680,
      "name": "filemap_get_read_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
    },
    {
      "addr": 18446744071597450055,
      "name": "filemap_get_read_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void filemap_get_read_batch(struct address_space * mapping, long unsigned int index, long unsigned int max, struct pagevec * pvec)
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
<code>struct folio_batch * fbatch</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pagevec * pvec</code>
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
