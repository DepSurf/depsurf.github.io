# Function: <code>memcg_kmem_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580504097,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:791",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_kmem_pages",
        "mm/page_alloc.c:alloc_kmem_pages_node"
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087680,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2344",
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
      "addr": 18446744071581087680,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162672,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2317",
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
      "addr": 18446744071581162672,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210400,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2326",
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
      "addr": 18446744071581210400,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340768,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2353",
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
      "addr": 18446744071581340768,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488240,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2340",
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
      "addr": 18446744071581488240,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573872,
      "name": "memcg_kmem_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2614",
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
      "addr": 18446744071581573872,
      "name": "memcg_kmem_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468710,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1316",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494780,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581832999,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1388",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490627240,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468444,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397366,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468364,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500099,
      "name": "memcg_kmem_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1402",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int memcg_kmem_charge(struct page * page, gfp_t gfp, int order)
```
</details>
</li>
</ul>
