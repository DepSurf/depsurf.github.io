# Function: <code>__memcg_slab_post_alloc_hook</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __memcg_slab_post_alloc_hook(struct kmem_cache * s, struct obj_cgroup * objcg, gfp_t flags, size_t size, void * * p)
```

```json
{
  "name": "__memcg_slab_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_slab_post_alloc_hook",
      "external": false,
      "loc": "mm/slub.c:1954",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390592,
      "name": "__memcg_slab_post_alloc_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071597464923,
      "name": "__memcg_slab_post_alloc_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void __memcg_slab_post_alloc_hook(struct kmem_cache * s, struct obj_cgroup * objcg, gfp_t flags, size_t size, void * * p)
```
</details>
</li>
</ul>
