# Function: <code>__kmem_cache_alloc_node</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * __kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller)
```

```json
{
  "name": "__kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224400,
      "name": "__kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3487",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_node_trace",
        "mm/slab_common.c:kmalloc_trace",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224400,
      "name": "__kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
void * __kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller)
```

```json
{
  "name": "__kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583443024,
      "name": "__kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3505",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmalloc_node_trace",
        "mm/slab_common.c:kmalloc_trace",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583443024,
      "name": "__kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * __kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void * __kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller)
```
</details>
</li>
</ul>
