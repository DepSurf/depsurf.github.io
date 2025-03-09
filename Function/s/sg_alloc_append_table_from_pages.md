# Function: <code>sg_alloc_append_table_from_pages</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "sg_alloc_append_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585214464,
      "name": "sg_alloc_append_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:442",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214464,
      "name": "sg_alloc_append_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1102
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
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "sg_alloc_append_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051552,
      "name": "sg_alloc_append_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:442",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051552,
      "name": "sg_alloc_append_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "sg_alloc_append_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036000,
      "name": "sg_alloc_append_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:451",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036000,
      "name": "sg_alloc_append_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1227
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
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "sg_alloc_append_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587293664,
      "name": "sg_alloc_append_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:453",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587293664,
      "name": "sg_alloc_append_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1221
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
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```

```json
{
  "name": "sg_alloc_append_table_from_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587579488,
      "name": "sg_alloc_append_table_from_pages",
      "external": true,
      "loc": "lib/scatterlist.c:454",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579488,
      "name": "sg_alloc_append_table_from_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int sg_alloc_append_table_from_pages(struct sg_append_table * sgt_append, struct page * * pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, unsigned int left_pages, gfp_t gfp_mask)
```
</details>
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
