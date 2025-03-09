# Function: <code>page_pool_use_xdp_mem</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588706976,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588706976,
      "name": "page_pool_use_xdp_mem",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589573264,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:502",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589573264,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589583312,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:552",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589583312,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589481120,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:585",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589481120,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590221280,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:694",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590221280,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect, struct xdp_mem_info * mem)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591798928,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:831",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591798928,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect, struct xdp_mem_info * mem)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593593344,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:832",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593593344,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect, struct xdp_mem_info * mem)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594066688,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:858",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594066688,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect, struct xdp_mem_info * mem)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594856128,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:929",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_reg_mem_model"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594856128,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502269328,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502269328,
      "name": "page_pool_use_xdp_mem",
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235010400,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235010400,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295765856,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295765856,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278504284,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278504284,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588313712,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313712,
      "name": "page_pool_use_xdp_mem",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026496,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026496,
      "name": "page_pool_use_xdp_mem",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645536,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645536,
      "name": "page_pool_use_xdp_mem",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
```

```json
{
  "name": "page_pool_use_xdp_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785120,
      "name": "page_pool_use_xdp_mem",
      "external": true,
      "loc": "net/core/page_pool.c:406",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785120,
      "name": "page_pool_use_xdp_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void page_pool_use_xdp_mem(struct page_pool * pool, void (*)(void *) disconnect)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_mem_info * mem</code>
</li>
</ul>
</details>
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
