# Function: <code>do_pages_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580888075,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1314",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581018258,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1495",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581092508,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1504",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581139335,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1492",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581261335,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1590",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581407667,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1563",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491155,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1596",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598960,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1591",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598960,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1389
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669520,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669520,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888848,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1634",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888848,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935312,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1755",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935312,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960816,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1737",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960816,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265616,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1781",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265616,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734512,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1711",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734512,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259056,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1821",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259056,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583479488,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:2157",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479488,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671904,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:2173",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671904,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493112992,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493112992,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1832
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286589248,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286589248,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2004
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638256,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638256,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579216,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579216,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629568,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629568,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "do_pages_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695872,
      "name": "do_pages_move",
      "external": false,
      "loc": "mm/migrate.c:1594",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:kernel_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695872,
      "name": "do_pages_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_pages_move(struct mm_struct * mm, nodemask_t task_nodes, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```
</details>
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
