# Function: <code>__memcg_kmem_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941120,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2438",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_kmem_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941120,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685584,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2878",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685584,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758464,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758464,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977744,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2929",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977744,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __memcg_kmem_uncharge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008365,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3109",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027504,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493212168,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493212168,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226842856,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226842856,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286722832,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286722832,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272988866,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272988866,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727200,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727200,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665984,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665984,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718512,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718512,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786400,
      "name": "__memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:3087",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786400,
      "name": "__memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __memcg_kmem_uncharge(struct page * page, int order)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __memcg_kmem_uncharge(struct page * page, int order)
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
void __memcg_kmem_uncharge(struct mem_cgroup * memcg, unsigned int nr_pages)
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
