# Function: <code>memcg_kmem_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580504226,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:804",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_kmem_pages"
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087888,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2366",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087888,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162880,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2339",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162880,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210608,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2348",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210608,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340992,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2375",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340992,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488448,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2362",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488448,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void memcg_kmem_uncharge(struct page * page, int order)
```

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574208,
      "name": "memcg_kmem_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:2636",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:put_task_stack",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/slub.c:__free_slab",
        "fs/pipe.c:anon_pipe_buf_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574208,
      "name": "memcg_kmem_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470808,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1323",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816684,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1323",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579496851,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889244,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581836237,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1396",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490621216,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493366160,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226953704,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286913136,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273086386,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470515,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857980,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399427,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795580,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470435,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849292,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
  "name": "memcg_kmem_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579502209,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918796,
      "name": "memcg_kmem_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:1409",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:anon_pipe_buf_steal"
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
void memcg_kmem_uncharge(struct page * page, int order)
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
void memcg_kmem_uncharge(struct page * page, int order)
```
</details>
</li>
</ul>
