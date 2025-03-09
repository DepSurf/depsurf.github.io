# Function: <code>alloc_slab_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580849946,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1374",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975605,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1398",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049429,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1397",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097262,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1399",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581216715,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1432",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581354047,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1433",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581437797,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1491",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548016,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1508",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548016,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612896,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612896,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832864,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1538",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832864,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581879587,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1611",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581911267,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1639",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582206656,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1763",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582671632,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1816",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583201360,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1843",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583419840,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1854",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583397075,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:2183",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493062176,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493062176,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226768852,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226768852,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286496560,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286496560,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272924734,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272924734,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581632,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581632,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581523200,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523200,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572944,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572944,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```

```json
{
  "name": "alloc_slab_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638032,
      "name": "alloc_slab_page",
      "external": false,
      "loc": "mm/slub.c:1488",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638032,
      "name": "alloc_slab_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
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
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct page * alloc_slab_page(struct kmem_cache * s, gfp_t flags, int node, struct kmem_cache_order_objects oo)
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
