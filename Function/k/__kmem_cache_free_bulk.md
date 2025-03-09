# Function: <code>__kmem_cache_free_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580632000,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:107",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632000,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734576,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:108",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734576,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800320,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:108",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800320,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839568,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:112",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839568,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930256,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:113",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930256,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066208,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:103",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066208,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144000,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:103",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144000,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210528,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210528,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269056,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269056,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459188,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459008,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581501940,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:107",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501760,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524132,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:115",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523952,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785828,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:115",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785648,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582171068,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:108",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170848,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583426046,
      "name": "__kmem_cache_free_bulk",
      "external": false,
      "loc": "mm/slub.c:4496",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_alloc_bulk"
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492673848,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492673848,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226512788,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226512788,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285998832,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285998832,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272681180,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272681180,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237904,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237904,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184576,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184576,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229104,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229104,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
```

```json
{
  "name": "__kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581292576,
      "name": "__kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slab_common.c:104",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292576,
      "name": "__kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache * s, size_t nr, void * * p)
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
