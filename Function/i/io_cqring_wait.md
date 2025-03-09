# Function: <code>io_cqring_wait</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2477",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176208,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071582196550,
      "name": "io_cqring_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253984,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253984,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542608,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:6299",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542608,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588736,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:7254",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588736,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602592,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:7035",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602592,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930448,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:7618",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930448,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986128,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "io_uring/io_uring.c:8927",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986128,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781696,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "io_uring/io_uring.c:2511",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781696,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1385
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040304,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "io_uring/io_uring.c:2549",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040304,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz, struct __kernel_timespec * uts)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587313552,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "io_uring/io_uring.c:2580",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313552,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1474
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
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493849312,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
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
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227349656,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287465900,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273419968,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222720,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222720,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160560,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160560,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213200,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213200,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "io_cqring_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291232,
      "name": "io_cqring_wait",
      "external": false,
      "loc": "fs/io_uring.c:2958",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291232,
      "name": "io_cqring_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct __kernel_timespec * uts</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int io_cqring_wait(struct io_ring_ctx * ctx, int min_events, const sigset_t * sig, size_t sigsz)
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
