# Function: <code>get_mem_cgroup_from_page</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552064,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:861",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552064,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666192,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:978",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666192,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738480,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738480,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955328,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:950",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955328,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001728,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:1053",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001728,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493190016,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493190016,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226823440,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226823440,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286692240,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286692240,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272972094,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272972094,
      "name": "get_mem_cgroup_from_page",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707216,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707216,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646208,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646208,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698528,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698528,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```

```json
{
  "name": "get_mem_cgroup_from_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766160,
      "name": "get_mem_cgroup_from_page",
      "external": true,
      "loc": "mm/memcontrol.c:989",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:alloc_page_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766160,
      "name": "get_mem_cgroup_from_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct mem_cgroup * get_mem_cgroup_from_page(struct page * page)
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
