# Function: <code>dma_direct_optimal_gfp_mask</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145568,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:48",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145568,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580125065,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580129410,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool",
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271968,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071592149888,
      "name": "dma_direct_optimal_gfp_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443312,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071593922594,
      "name": "dma_direct_optimal_gfp_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687520,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071595992999,
      "name": "dma_direct_optimal_gfp_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764128,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071596511259,
      "name": "dma_direct_optimal_gfp_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 * phys_limit)
```

```json
{
  "name": "dma_direct_optimal_gfp_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_optimal_gfp_mask",
      "external": false,
      "loc": "kernel/dma/direct.c:47",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_from_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849872,
      "name": "dma_direct_optimal_gfp_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071597410248,
      "name": "dma_direct_optimal_gfp_mask.cold",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device * dev, u64 dma_mask, u64 * phys_limit)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 dma_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, dma_mask, phys_limit</code> ➡️ <code>dev, phys_limit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
