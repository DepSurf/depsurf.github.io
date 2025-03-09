# Function: <code>split_free_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int split_free_page(struct page * page)
```

```json
{
  "name": "split_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505680,
      "name": "split_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505680,
      "name": "split_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int split_free_page(struct page * free_page, unsigned int order, long unsigned int split_pfn_offset)
```

```json
{
  "name": "split_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "split_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:1114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593980806,
      "name": "split_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071582428448,
      "name": "split_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
int split_free_page(struct page * free_page, unsigned int order, long unsigned int split_pfn_offset)
```

```json
{
  "name": "split_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "split_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:1186",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596036392,
      "name": "split_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071582937088,
      "name": "split_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 913
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
int split_free_page(struct page * free_page, unsigned int order, long unsigned int split_pfn_offset)
```

```json
{
  "name": "split_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "split_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:882",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596558505,
      "name": "split_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071583154512,
      "name": "split_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
int split_free_page(struct page * free_page, unsigned int order, long unsigned int split_pfn_offset)
```

```json
{
  "name": "split_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "split_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:858",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597462866,
      "name": "split_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071583337584,
      "name": "split_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int split_free_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int split_free_page(struct page * free_page, unsigned int order, long unsigned int split_pfn_offset)
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
