# Function: <code>page_pool_return_page</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589571307,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:312",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589580233,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:314",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589477257,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:353",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590216210,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:379",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591792627,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:499",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593586515,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:500",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594059539,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:525",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void page_pool_return_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_return_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_return_page",
      "external": false,
      "loc": "net/core/page_pool.c:576",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_unrefed_page",
        "net/core/page_pool.c:page_pool_put_unrefed_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594849840,
      "name": "page_pool_return_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071597784348,
      "name": "page_pool_return_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void page_pool_return_page(struct page_pool * pool, struct page * page)
```
</details>
</li>
</ul>
