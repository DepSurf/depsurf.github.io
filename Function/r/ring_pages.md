# Function: <code>ring_pages</code>

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
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582191275,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:2824",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271328,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271328,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582500000,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:7205",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582500000,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557664,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:8373",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557664,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493835952,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493835952,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227344796,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227344796,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287468912,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287468912,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273416818,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273416818,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240064,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240064,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177808,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177808,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230544,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230544,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```

```json
{
  "name": "ring_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308816,
      "name": "ring_pages",
      "external": false,
      "loc": "fs/io_uring.c:3380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308816,
      "name": "ring_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
```
</details>
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
long unsigned int ring_pages(unsigned int sq_entries, unsigned int cq_entries)
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
