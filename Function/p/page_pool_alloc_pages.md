# Function: <code>page_pool_alloc_pages</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588011024,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:159",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588011024,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171760,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:159",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171760,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588497664,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:179",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588497664,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588704816,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588704816,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589572608,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:245",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572608,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589582624,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:247",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589582624,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480432,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:286",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480432,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590220941,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:310",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_alloc_frag"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219488,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591798573,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:430",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_alloc_frag"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591796816,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593592973,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:431",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_alloc_frag"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592624,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594066281,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:456",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_alloc_frag"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594065904,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594854449,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:512",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_alloc_frag"
      ],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594854096,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502268056,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502268056,
      "name": "page_pool_alloc_pages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235008300,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235008300,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295762432,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295762432,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278503320,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278503320,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311552,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311552,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024336,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024336,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588643376,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588643376,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```

```json
{
  "name": "page_pool_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782912,
      "name": "page_pool_alloc_pages",
      "external": true,
      "loc": "net/core/page_pool.c:175",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782912,
      "name": "page_pool_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct page * page_pool_alloc_pages(struct page_pool * pool, gfp_t gfp)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
