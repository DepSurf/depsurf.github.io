# Function: <code>page_pool_unmap_page</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496016,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:243",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496016,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703936,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703936,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502266312,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502266312,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235007420,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235007420,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295761232,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295761232,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278501700,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278501700,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310672,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310672,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588023456,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023456,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642496,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642496,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```

```json
{
  "name": "page_pool_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782000,
      "name": "page_pool_unmap_page",
      "external": true,
      "loc": "net/core/page_pool.c:234",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_release_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782000,
      "name": "page_pool_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void page_pool_unmap_page(struct page_pool * pool, struct page * page)
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
