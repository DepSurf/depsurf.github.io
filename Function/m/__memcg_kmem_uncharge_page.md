# Function: <code>__memcg_kmem_uncharge_page</code>

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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978224,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:2972",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978224,
      "name": "__memcg_kmem_uncharge_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028064,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3148",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028064,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054272,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:2992",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054272,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3060",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225642,
      "name": "__memcg_kmem_uncharge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582361200,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3041",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exit_task_stack_account",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004710,
      "name": "__memcg_kmem_uncharge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582858368,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3141",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exit_task_stack_account",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596049006,
      "name": "__memcg_kmem_uncharge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583405600,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3151",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exit_task_stack_account",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571475,
      "name": "__memcg_kmem_uncharge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583625904,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
```

```json
{
  "name": "__memcg_kmem_uncharge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__memcg_kmem_uncharge_page",
      "external": true,
      "loc": "mm/memcontrol.c:3343",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:exit_task_stack_account",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok",
        "fs/pipe.c:anon_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475970,
      "name": "__memcg_kmem_uncharge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583820528,
      "name": "__memcg_kmem_uncharge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void __memcg_kmem_uncharge_page(struct page * page, int order)
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
