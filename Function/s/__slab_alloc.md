# Function: <code>__slab_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855216,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2451",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855216,
      "name": "__slab_alloc",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983824,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2580",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983824,
      "name": "__slab_alloc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057664,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057664,
      "name": "__slab_alloc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105504,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2599",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105504,
      "name": "__slab_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220512,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2612",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220512,
      "name": "__slab_alloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361600,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2595",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361600,
      "name": "__slab_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446896,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2645",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446896,
      "name": "__slab_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559952,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2651",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559952,
      "name": "__slab_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624976,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624976,
      "name": "__slab_alloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841696,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2698",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841696,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892144,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2765",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892144,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926090,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2782",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922768,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582223539,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:3074",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582689380,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:3104",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583214715,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:3278",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583433107,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:3300",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583414306,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:3611",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493071736,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493071736,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226796892,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286539688,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller"
      ],
      "caller_func": [
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286514000,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272947268,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593712,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593712,
      "name": "__slab_alloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581551309,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller"
      ],
      "caller_func": [
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535152,
      "name": "__slab_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581585024,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585024,
      "name": "__slab_alloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__slab_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581650672,
      "name": "__slab_alloc",
      "external": false,
      "loc": "mm/slub.c:2640",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650672,
      "name": "__slab_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void * __slab_alloc(struct kmem_cache * s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu * c)
```
</details>
</li>
</ul>
