# Function: <code>__alloc_page_frag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __alloc_page_frag(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "__alloc_page_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513328,
      "name": "__alloc_page_frag",
      "external": true,
      "loc": "mm/page_alloc.c:3337",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__napi_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513328,
      "name": "__alloc_page_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * __alloc_page_frag(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "__alloc_page_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595024,
      "name": "__alloc_page_frag",
      "external": true,
      "loc": "mm/page_alloc.c:3805",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595024,
      "name": "__alloc_page_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void * __alloc_page_frag(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```
</details>
</li>
</ul>
