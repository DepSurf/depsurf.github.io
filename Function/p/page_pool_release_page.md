# Function: <code>page_pool_release_page</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588479195,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:197",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588684603,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589570640,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570640,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589580016,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:286",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_empty_ring",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580016,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589476912,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:325",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476912,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:349",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592704031,
      "name": "page_pool_release_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071590215776,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:469",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594590683,
      "name": "page_pool_release_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071591792160,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:470",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596329075,
      "name": "page_pool_release_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071593586016,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_pool_release_page",
      "external": true,
      "loc": "net/core/page_pool.c:495",
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
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_refill_alloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596859242,
      "name": "page_pool_release_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071594059040,
      "name": "page_pool_release_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502240740,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232575244,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3234985656,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295732416,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278481786,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588291339,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588004155,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588623163,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
  "name": "page_pool_release_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588761155,
      "name": "page_pool_release_page",
      "external": false,
      "loc": "include/net/page_pool.h:178",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame"
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
void page_pool_release_page(struct page_pool * pool, struct page * page)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void page_pool_release_page(struct page_pool * pool, struct page * page)
```
</details>
</li>
</ul>
