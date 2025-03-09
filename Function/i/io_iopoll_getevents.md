# Function: <code>io_iopoll_getevents</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181168,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:778",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181168,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260288,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260288,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582537267,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:1890",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535328,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:2542",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_check"
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493836104,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493836104,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227342756,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227342756,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287455184,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287455184,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273408534,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273408534,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229024,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229024,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166832,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166832,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219504,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219504,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_getevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305168,
      "name": "io_iopoll_getevents",
      "external": false,
      "loc": "fs/io_uring.c:849",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305168,
      "name": "io_iopoll_getevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int io_iopoll_getevents(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
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
