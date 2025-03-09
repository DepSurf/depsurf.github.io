# Function: <code>page_pool_destroy</code>

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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010944,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:296",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010944,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171680,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:296",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171680,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588706192,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588706192,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589571808,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:508",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589571808,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589581056,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:558",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_page_pool",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589581056,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589478176,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:591",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589478176,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590219600,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:700",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219600,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591796944,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:839",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591796944,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593589648,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:840",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593589648,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594062800,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:881",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594062800,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594855472,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:952",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "net/core/xdp.c:xdp_unreg_mem_model",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594855472,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502267232,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502267232,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235009576,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_destroy_xdp_rxqs",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235009576,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295764432,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295764432,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278502978,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278502978,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588312928,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312928,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588025712,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025712,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588644752,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644752,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void page_pool_destroy(struct page_pool * pool)
```

```json
{
  "name": "page_pool_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588784336,
      "name": "page_pool_destroy",
      "external": true,
      "loc": "net/core/page_pool.c:412",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784336,
      "name": "page_pool_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void page_pool_destroy(struct page_pool * pool)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void page_pool_destroy(struct page_pool * pool)
```
</details>
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
