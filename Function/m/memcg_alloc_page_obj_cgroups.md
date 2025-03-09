# Function: <code>memcg_alloc_page_obj_cgroups</code>

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
int memcg_alloc_page_obj_cgroups(struct page * page, struct kmem_cache * s, gfp_t gfp)
```

```json
{
  "name": "memcg_alloc_page_obj_cgroups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026336,
      "name": "memcg_alloc_page_obj_cgroups",
      "external": true,
      "loc": "mm/memcontrol.c:2933",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026336,
      "name": "memcg_alloc_page_obj_cgroups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int memcg_alloc_page_obj_cgroups(struct page * page, struct kmem_cache * s, gfp_t gfp, bool new_page)
```

```json
{
  "name": "memcg_alloc_page_obj_cgroups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052736,
      "name": "memcg_alloc_page_obj_cgroups",
      "external": true,
      "loc": "mm/memcontrol.c:2749",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052736,
      "name": "memcg_alloc_page_obj_cgroups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int memcg_alloc_page_obj_cgroups(struct page * page, struct kmem_cache * s, gfp_t gfp, bool new_page)
```

```json
{
  "name": "memcg_alloc_page_obj_cgroups",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359536,
      "name": "memcg_alloc_page_obj_cgroups",
      "external": true,
      "loc": "mm/memcontrol.c:2817",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359536,
      "name": "memcg_alloc_page_obj_cgroups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
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
int memcg_alloc_page_obj_cgroups(struct page * page, struct kmem_cache * s, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool new_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int memcg_alloc_page_obj_cgroups(struct page * page, struct kmem_cache * s, gfp_t gfp, bool new_page)
```
</details>
</li>
</ul>
