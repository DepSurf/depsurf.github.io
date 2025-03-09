# Function: <code>memcg_kmem_get_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855656,
      "name": "memcg_kmem_get_cache",
      "external": false,
      "loc": "include/linux/memcontrol.h:818",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087120,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2254",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087120,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162112,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2227",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162112,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209792,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2236",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209792,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340160,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2263",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340160,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487648,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2250",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487648,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573168,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2527",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573168,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684496,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2729",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684496,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757360,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757360,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977008,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2815",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977008,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
    }
  ]
}
```
</details>
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493211024,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493211024,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226841276,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226841276,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286720832,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286720832,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272987630,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272987630,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726096,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726096,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664880,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664880,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717408,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717408,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```

```json
{
  "name": "memcg_kmem_get_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785104,
      "name": "memcg_kmem_get_cache",
      "external": true,
      "loc": "mm/memcontrol.c:2928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785104,
      "name": "memcg_kmem_get_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
```
</details>
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
struct kmem_cache * memcg_kmem_get_cache(struct kmem_cache * cachep)
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
