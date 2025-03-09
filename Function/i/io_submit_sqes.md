# Function: <code>io_submit_sqes</code>

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
int io_submit_sqes(struct io_ring_ctx * ctx, struct sqe_submit * sqes, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189776,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2260",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189776,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269872,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269872,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, struct file * ring_file, int ring_fd)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582550432,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:6059",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550432,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1409
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619152,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:6918",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619152,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1455
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648704,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:6743",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648704,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:7327",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972320,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1497
    },
    {
      "addr": 18446744071592238424,
      "name": "io_submit_sqes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "io_uring/io_uring.c:8634",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013408,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
    },
    {
      "addr": 18446744071594122298,
      "name": "io_submit_sqes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_submit_sqes",
      "external": true,
      "loc": "io_uring/io_uring.c:2370",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596111556,
      "name": "io_submit_sqes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586780544,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_submit_sqes",
      "external": true,
      "loc": "io_uring/io_uring.c:2397",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635913,
      "name": "io_submit_sqes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587047440,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_submit_sqes",
      "external": true,
      "loc": "io_uring/io_uring.c:2428",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597543615,
      "name": "io_submit_sqes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587322672,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493850192,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493850192,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227342228,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227342228,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287467008,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287467008,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273414570,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273414570,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238608,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238608,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176352,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176352,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229088,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229088,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int io_submit_sqes(struct io_ring_ctx * ctx, unsigned int nr, bool has_user, bool mm_fault)
```

```json
{
  "name": "io_submit_sqes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304528,
      "name": "io_submit_sqes",
      "external": false,
      "loc": "fs/io_uring.c:2668",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304528,
      "name": "io_submit_sqes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int io_submit_sqes(struct io_ring_ctx * ctx, struct sqe_submit * sqes, unsigned int nr, bool has_user, bool mm_fault)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sqe_submit * sqes</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, sqes, nr, has_user, mm_fault</code> ➡️ <code>ctx, nr, has_user, mm_fault</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * ring_file</code>
</li>
<li>
<b>Param added. </b>
<code>int ring_fd</code>
</li>
<li>
<b>Param removed. </b>
<code>bool has_user</code>
</li>
<li>
<b>Param removed. </b>
<code>bool mm_fault</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file * ring_file</code>
</li>
<li>
<b>Param removed. </b>
<code>int ring_fd</code>
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
