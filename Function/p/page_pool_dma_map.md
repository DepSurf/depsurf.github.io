# Function: <code>page_pool_dma_map</code>

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
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589477072,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:185",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589477072,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:192",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590215984,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071592704061,
      "name": "page_pool_dma_map.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:307",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591792384,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071594590713,
      "name": "page_pool_dma_map.cold",
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
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:307",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593586256,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596329105,
      "name": "page_pool_dma_map.cold",
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
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:331",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594059280,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596859272,
      "name": "page_pool_dma_map.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_dma_map",
      "external": false,
      "loc": "net/core/page_pool.c:371",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594849648,
      "name": "page_pool_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071597784310,
      "name": "page_pool_dma_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
bool page_pool_dma_map(struct page_pool * pool, struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
