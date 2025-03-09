# Function: <code>new_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849824,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1491",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849824,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975472,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1623",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975472,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1749
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049296,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1626",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049296,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1761
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097104,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1628",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097104,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216576,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1643",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216576,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1645
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1646",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353904,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1789
    },
    {
      "addr": 18446744071581380255,
      "name": "new_slab.cold.92",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1705",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437664,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1850
    },
    {
      "addr": 18446744071581464367,
      "name": "new_slab.cold.94",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1717",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550032,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581578712,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614848,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581643909,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581834802,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1746",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834656,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581859403,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581880674,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1816",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581912370,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1844",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582207810,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1963",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207680,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct slab * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582700433,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:2022",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:init_kmem_cache_nodes"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672736,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct slab * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583202308,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:2044",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202160,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct slab * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583420794,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:2055",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420640,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct slab * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583398010,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:2400",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397856,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493064328,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493064328,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226770908,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226770908,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286499456,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286499456,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272926564,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272926564,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583584,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581612645,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525104,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581553973,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574896,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581603957,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "new_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "new_slab",
      "external": false,
      "loc": "mm/slub.c:1696",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640144,
      "name": "new_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071581669925,
      "name": "new_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct page * new_slab(struct kmem_cache * s, gfp_t flags, int node)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct slab *</code>
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
