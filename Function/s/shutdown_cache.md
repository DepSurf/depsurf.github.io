# Function: <code>shutdown_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580627092,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:450",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580732771,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:455",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580798547,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:461",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835264,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:528",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835264,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925952,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:537",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925952,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061936,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:558",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061936,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139744,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:585",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_destroy_kmem_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139744,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581207856,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:600",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207856,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264048,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264048,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455360,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:shutdown_memcg_caches",
        "mm/slab_common.c:shutdown_memcg_caches",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455360,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581499185,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:447",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581520605,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:460",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581782279,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:461",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582169651,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:457",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582649767,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:452",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582859303,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:452",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583034775,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:447",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy"
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492665736,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492665736,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226507428,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226507428,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285990768,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285990768,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272676768,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272676768,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232896,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232896,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179568,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179568,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224096,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224096,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int shutdown_cache(struct kmem_cache * s)
```

```json
{
  "name": "shutdown_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287520,
      "name": "shutdown_cache",
      "external": false,
      "loc": "mm/slab_common.c:601",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:kmemcg_cache_shutdown_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287520,
      "name": "shutdown_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int shutdown_cache(struct kmem_cache * s)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int shutdown_cache(struct kmem_cache * s)
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
