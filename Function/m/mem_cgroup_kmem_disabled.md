# Function: <code>mem_cgroup_kmem_disabled</code>

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
bool mem_cgroup_kmem_disabled()
```

```json
{
  "name": "mem_cgroup_kmem_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_kmem_disabled",
      "external": true,
      "loc": "mm/memcontrol.c:259",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592224924,
      "name": "mem_cgroup_kmem_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582343808,
      "name": "mem_cgroup_kmem_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool mem_cgroup_kmem_disabled()
```

```json
{
  "name": "mem_cgroup_kmem_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_kmem_disabled",
      "external": true,
      "loc": "mm/memcontrol.c:258",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/slab_common.c:new_kmalloc_cache",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004014,
      "name": "mem_cgroup_kmem_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582838336,
      "name": "mem_cgroup_kmem_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mem_cgroup_kmem_disabled()
```

```json
{
  "name": "mem_cgroup_kmem_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583387988,
      "name": "mem_cgroup_kmem_disabled",
      "external": true,
      "loc": "mm/memcontrol.c:251",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596048699,
      "name": "mem_cgroup_kmem_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583383408,
      "name": "mem_cgroup_kmem_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mem_cgroup_kmem_disabled()
```

```json
{
  "name": "mem_cgroup_kmem_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583608916,
      "name": "mem_cgroup_kmem_disabled",
      "external": true,
      "loc": "mm/memcontrol.c:255",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571173,
      "name": "mem_cgroup_kmem_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583603984,
      "name": "mem_cgroup_kmem_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mem_cgroup_kmem_disabled()
```

```json
{
  "name": "mem_cgroup_kmem_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583803740,
      "name": "mem_cgroup_kmem_disabled",
      "external": true,
      "loc": "mm/memcontrol.c:259",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_online"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475641,
      "name": "mem_cgroup_kmem_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583798512,
      "name": "mem_cgroup_kmem_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool mem_cgroup_kmem_disabled()
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
