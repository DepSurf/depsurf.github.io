# Function: <code>flush_all_cpus_locked</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_all_cpus_locked(struct kmem_cache * s)
```

```json
{
  "name": "flush_all_cpus_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_all_cpus_locked",
      "external": false,
      "loc": "mm/slub.c:2674",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:validate_slab_cache",
        "mm/slub.c:slab_memory_callback",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200000,
      "name": "flush_all_cpus_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071592218278,
      "name": "flush_all_cpus_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void flush_all_cpus_locked(struct kmem_cache * s)
```

```json
{
  "name": "flush_all_cpus_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_all_cpus_locked",
      "external": false,
      "loc": "mm/slub.c:2716",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:validate_slab_cache",
        "mm/slub.c:slab_memory_callback",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664960,
      "name": "flush_all_cpus_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071593997327,
      "name": "flush_all_cpus_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void flush_all_cpus_locked(struct kmem_cache * s)
```

```json
{
  "name": "flush_all_cpus_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_all_cpus_locked",
      "external": false,
      "loc": "mm/slub.c:2805",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:validate_slab_cache",
        "mm/slub.c:slab_memory_callback",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191488,
      "name": "flush_all_cpus_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071596045112,
      "name": "flush_all_cpus_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void flush_all_cpus_locked(struct kmem_cache * s)
```

```json
{
  "name": "flush_all_cpus_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_all_cpus_locked",
      "external": false,
      "loc": "mm/slub.c:2815",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:validate_slab_cache",
        "mm/slub.c:slab_memory_callback",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409520,
      "name": "flush_all_cpus_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071596567547,
      "name": "flush_all_cpus_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void flush_all_cpus_locked(struct kmem_cache * s)
```

```json
{
  "name": "flush_all_cpus_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_all_cpus_locked",
      "external": false,
      "loc": "mm/slub.c:3089",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:validate_slab_cache",
        "mm/slub.c:slab_memory_callback",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389248,
      "name": "flush_all_cpus_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071597464827,
      "name": "flush_all_cpus_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void flush_all_cpus_locked(struct kmem_cache * s)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
