# Function: <code>io_mem_alloc</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582191857,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:2816",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582272733,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582500563,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:7168",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_allocate_scq_urings",
        "fs/io_uring.c:io_allocate_scq_urings"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556672,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:8336",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_allocate_scq_urings",
        "fs/io_uring.c:io_allocate_scq_urings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556672,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584320,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:8121",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584320,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582900928,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:8834",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582900928,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594111162,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "io_uring/io_uring.c:10124",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_allocate_scq_urings",
        "io_uring/io_uring.c:io_allocate_scq_urings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594111162,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586744992,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "io_uring/io_uring.c:2595",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_allocate_scq_urings",
        "io_uring/io_uring.c:io_allocate_scq_urings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586744992,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009664,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "io_uring/io_uring.c:2743",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_allocate_scq_urings",
        "io_uring/io_uring.c:io_allocate_scq_urings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009664,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void * io_mem_alloc(size_t size)
```

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587325328,
      "name": "io_mem_alloc",
      "external": true,
      "loc": "io_uring/io_uring.c:2803",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_allocate_scq_urings",
        "io_uring/io_uring.c:io_allocate_scq_urings",
        "io_uring/kbuf.c:io_register_pbuf_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325328,
      "name": "io_mem_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493838396,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227346268,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287470532,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273418362,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582241469,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582179197,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582231949,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
  "name": "io_mem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582310205,
      "name": "io_mem_alloc",
      "external": false,
      "loc": "fs/io_uring.c:3343",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void * io_mem_alloc(size_t size)
```
</details>
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
