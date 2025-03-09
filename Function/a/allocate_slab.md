# Function: <code>allocate_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580849859,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1395",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975537,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1522",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049361,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1525",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097170,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1527",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581216642,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1558",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581353964,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1561",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581437724,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1619",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548880,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1636",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548880,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613664,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613664,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833600,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1666",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833600,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879472,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1734",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879472,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911152,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1762",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911152,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1886",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206560,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
    },
    {
      "addr": 18446744071592219300,
      "name": "allocate_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct slab * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1948",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:init_kmem_cache_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671536,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    },
    {
      "addr": 18446744071593998276,
      "name": "allocate_slab.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct slab * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1977",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201248,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
    },
    {
      "addr": 18446744071596045914,
      "name": "allocate_slab.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct slab * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1988",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419728,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 881
    },
    {
      "addr": 18446744071596568379,
      "name": "allocate_slab.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct slab * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:2333",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:early_kmem_cache_node_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396960,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
    },
    {
      "addr": 18446744071597465458,
      "name": "allocate_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493063120,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493063120,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226769784,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226769784,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286497936,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286497936,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1508
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272925532,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272925532,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582400,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582400,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581523952,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523952,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1141
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573712,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573712,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
```

```json
{
  "name": "allocate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638960,
      "name": "allocate_slab",
      "external": false,
      "loc": "mm/slub.c:1616",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638960,
      "name": "allocate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
struct page * allocate_slab(struct kmem_cache * s, gfp_t flags, int node)
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
