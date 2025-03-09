# Function: <code>__sg_alloc_table_from_pages</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583628272,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:393",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628272,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583844400,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:381",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844400,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583928096,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:381",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928096,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108974,
      "name": "__sg_alloc_table_from_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584108016,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584231184,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231184,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637648,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637648,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scatterlist * __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, struct scatterlist * prv, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756656,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:428",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756656,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1073
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scatterlist * __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, struct scatterlist * prv, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784240,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:428",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784240,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496106224,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496106224,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229431656,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229431656,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290353568,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290353568,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275172576,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275172576,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584199920,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199920,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584135136,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135136,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584183680,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183680,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```

```json
{
  "name": "__sg_alloc_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288032,
      "name": "__sg_alloc_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:389",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288032,
      "name": "__sg_alloc_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scatterlist * prv</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int left_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>sgt, pages, n_pages, offset, size, max_segment, gfp_mask</code> ➡️ <code>sgt, pages, n_pages, offset, size, max_segment, prv, left_pages, gfp_mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct scatterlist *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct scatterlist * __sg_alloc_table_from_pages(struct sg_table * sgt, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, struct scatterlist * prv, unsigned int left_pages, gfp_t gfp_mask)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
