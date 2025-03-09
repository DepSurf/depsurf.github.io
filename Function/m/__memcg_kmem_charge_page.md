# Function: <code>__memcg_kmem_charge_page</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977856,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:2947",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:memcg_charge_kernel_stack",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977856,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027568,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3125",
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
      "addr": 18446744071582027568,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053696,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:2969",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053696,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3037",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225617,
      "name": "__memcg_kmem_charge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582360624,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3018",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004685,
      "name": "__memcg_kmem_charge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582857680,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3118",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596048981,
      "name": "__memcg_kmem_charge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583404896,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3128",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571450,
      "name": "__memcg_kmem_charge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583625200,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```

```json
{
  "name": "__memcg_kmem_charge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_charge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3320",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475939,
      "name": "__memcg_kmem_charge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583820000,
      "name": "__memcg_kmem_charge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __memcg_kmem_charge_page(struct page * page, gfp_t gfp, int order)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
