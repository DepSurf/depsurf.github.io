# Function: <code>page_pool_put_page</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587998245,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:118",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588157818,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:118",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588479946,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:156",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588685338,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589572688,
      "name": "page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:365",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572688,
      "name": "page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589582704,
      "name": "page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589582704,
      "name": "page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480512,
      "name": "page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:445",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480512,
      "name": "page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590220000,
      "name": "page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:476",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return",
        "net/core/page_pool.c:page_pool_return_skb_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590220000,
      "name": "page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591762248,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:314",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591798225,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:314",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page"
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
  "name": "page_pool_put_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593553262,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:314",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593590961,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:314",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page"
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
  "name": "page_pool_put_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594022606,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:330",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594064182,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:330",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_skb_page"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594382055,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool/helpers.h:304",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:napi_pp_put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594809220,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool/helpers.h:304",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502243124,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234988476,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295735592,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278483740,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588292074,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588004890,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588623898,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588761915,
      "name": "page_pool_put_page",
      "external": false,
      "loc": "include/net/page_pool.h:155",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void page_pool_put_page(struct page_pool * pool, struct page * page, unsigned int dma_sync_size, bool allow_direct)
```
</details>
</li>
</ul>
