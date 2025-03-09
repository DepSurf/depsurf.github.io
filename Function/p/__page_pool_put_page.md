# Function: <code>__page_pool_put_page</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588011568,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:227",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588011568,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588172304,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:227",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172304,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588498224,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:293",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588498224,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588706448,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588706448,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589581527,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:368",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589478647,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:399",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590217412,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:425",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591793977,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:553",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593587993,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:554",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594061033,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:579",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page"
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
  "name": "__page_pool_put_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594851163,
      "name": "__page_pool_put_page",
      "external": false,
      "loc": "net/core/page_pool.c:640",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_unrefed_page"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502268680,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502268680,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235009956,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235009956,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295764960,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295764960,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278503832,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278503832,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313184,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313184,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588025968,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025968,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588645008,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645008,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
```

```json
{
  "name": "__page_pool_put_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588784592,
      "name": "__page_pool_put_page",
      "external": true,
      "loc": "net/core/page_pool.c:284",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784592,
      "name": "__page_pool_put_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __page_pool_put_page(struct page_pool * pool, struct page * page, bool allow_direct)
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
