# Function: <code>__memcg_kmem_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940976,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2427",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_kmem_pages",
        "mm/page_alloc.c:alloc_kmem_pages_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940976,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685136,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2838",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685136,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758016,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758016,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __memcg_kmem_charge(struct mem_cgroup * memcg, gfp_t gfp, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581977552,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2896",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977552,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __memcg_kmem_charge(struct mem_cgroup * memcg, gfp_t gfp, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582027264,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3076",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027264,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493211752,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493211752,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226842204,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226842204,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286722000,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286722000,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272988332,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272988332,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726752,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726752,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665536,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665536,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718064,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718064,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785872,
      "name": "__memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:3047",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785872,
      "name": "__memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param removed. </b>
<code>int order</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __memcg_kmem_charge(struct mem_cgroup * memcg, gfp_t gfp, unsigned int nr_pages)
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
