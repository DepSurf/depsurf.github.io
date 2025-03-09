# Function: <code>page_frag_alloc_align</code>

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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745920,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:5333",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745920,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:5514",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204824,
      "name": "page_frag_alloc_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582024096,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:5569",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593982163,
      "name": "page_frag_alloc_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582450832,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:5696",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037696,
      "name": "page_frag_alloc_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582962672,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:4624",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559929,
      "name": "page_frag_alloc_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583179776,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
```

```json
{
  "name": "page_frag_alloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_frag_alloc_align",
      "external": true,
      "loc": "mm/page_alloc.c:4713",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__netdev_alloc_frag_align",
        "net/core/skbuff.c:__napi_alloc_frag_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464344,
      "name": "page_frag_alloc_align.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583363264,
      "name": "page_frag_alloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
void * page_frag_alloc_align(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask)
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
