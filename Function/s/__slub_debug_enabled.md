# Function: <code>__slub_debug_enabled</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __slub_debug_enabled()
```

```json
{
  "name": "__slub_debug_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582202115,
      "name": "__slub_debug_enabled",
      "external": false,
      "loc": "mm/slab.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:kmem_obj_info",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592217357,
      "name": "__slub_debug_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
bool __slub_debug_enabled()
```

```json
{
  "name": "__slub_debug_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582667571,
      "name": "__slub_debug_enabled",
      "external": false,
      "loc": "mm/slab.h:406",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:setup_object"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593996540,
      "name": "__slub_debug_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__slub_debug_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583216926,
      "name": "__slub_debug_enabled",
      "external": false,
      "loc": "mm/slab.h:412",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:free_partial",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:calculate_sizes",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:free_slab",
        "mm/slub.c:free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:shuffle_freelist",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:check_object",
        "mm/slub.c:check_object",
        "mm/slub.c:init_object",
        "mm/slub.c:init_object",
        "mm/slub.c:print_trailer",
        "mm/slub.c:skip_orig_size_check",
        "mm/slub.c:kmem_cache_init"
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
  "name": "__slub_debug_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583435406,
      "name": "__slub_debug_enabled",
      "external": false,
      "loc": "mm/slab.h:404",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:free_partial",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:calculate_sizes",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:__kmem_cache_alloc_bulk",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:free_slab",
        "mm/slub.c:free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:shuffle_freelist",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:check_object",
        "mm/slub.c:check_object",
        "mm/slub.c:init_object",
        "mm/slub.c:init_object",
        "mm/slub.c:print_trailer",
        "mm/slub.c:skip_orig_size_check",
        "mm/slub.c:kmem_cache_init"
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
  "name": "__slub_debug_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583402574,
      "name": "__slub_debug_enabled",
      "external": false,
      "loc": "mm/slab.h:516",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:free_partial",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:calculate_sizes",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:free_slab",
        "mm/slub.c:free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:shuffle_freelist",
        "mm/slub.c:setup_object",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:check_object",
        "mm/slub.c:check_object",
        "mm/slub.c:init_object",
        "mm/slub.c:init_object",
        "mm/slub.c:print_trailer",
        "mm/slub.c:skip_orig_size_check",
        "mm/slub.c:kmem_cache_init"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool __slub_debug_enabled()
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool __slub_debug_enabled()
```
</details>
</li>
</ul>
