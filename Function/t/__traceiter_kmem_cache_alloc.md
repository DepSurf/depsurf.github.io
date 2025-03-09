# Function: <code>__traceiter_kmem_cache_alloc</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, size_t bytes_req, size_t bytes_alloc, gfp_t gfp_flags)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492304,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:54",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492304,
      "name": "__traceiter_kmem_cache_alloc",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, size_t bytes_req, size_t bytes_alloc, gfp_t gfp_flags)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513488,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:54",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513488,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, size_t bytes_req, size_t bytes_alloc, gfp_t gfp_flags)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775056,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:54",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775056,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, size_t bytes_req, size_t bytes_alloc, gfp_t gfp_flags)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158608,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:54",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158608,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, struct kmem_cache * s, gfp_t gfp_flags, int node)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638256,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:12",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638256,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, struct kmem_cache * s, gfp_t gfp_flags, int node)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847504,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:12",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847504,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, struct kmem_cache * s, gfp_t gfp_flags, int node)
```

```json
{
  "name": "__traceiter_kmem_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022144,
      "name": "__traceiter_kmem_cache_alloc",
      "external": true,
      "loc": "include/trace/events/kmem.h:12",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022144,
      "name": "__traceiter_kmem_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __traceiter_kmem_cache_alloc(void * __data, long unsigned int call_site, const void * ptr, size_t bytes_req, size_t bytes_alloc, gfp_t gfp_flags)
```
</details>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kmem_cache * s</code>
</li>
<li>
<b>Param added. </b>
<code>int node</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t bytes_req</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t bytes_alloc</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, call_site, ptr, bytes_req, bytes_alloc, gfp_flags</code> ➡️ <code>__data, call_site, ptr, s, gfp_flags, node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
