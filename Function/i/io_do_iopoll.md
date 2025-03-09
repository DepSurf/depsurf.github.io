# Function: <code>io_do_iopoll</code>

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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582181286,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:728",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582260406,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int io_do_iopoll(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535024,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:1840",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535024,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int io_do_iopoll(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606144,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:2488",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sq_thread",
        "fs/io_uring.c:io_iopoll_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606144,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int io_do_iopoll(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min, bool resubmit)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619568,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:2308",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619568,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
int io_do_iopoll(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:2508",
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
      "addr": 18446744071582943408,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071592238026,
      "name": "io_do_iopoll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int io_do_iopoll(struct io_ring_ctx * ctx, bool force_nonspin)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "io_uring/io_uring.c:3007",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io_uring.c:io_iopoll_try_reap_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014576,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071594122670,
      "name": "io_do_iopoll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int io_do_iopoll(struct io_ring_ctx * ctx, bool force_nonspin)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_do_iopoll",
      "external": true,
      "loc": "io_uring/rw.c:999",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_iopoll_check",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596112430,
      "name": "io_do_iopoll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586860144,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
int io_do_iopoll(struct io_ring_ctx * ctx, bool force_nonspin)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_do_iopoll",
      "external": true,
      "loc": "io_uring/rw.c:1001",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_iopoll_check",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596636929,
      "name": "io_do_iopoll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587126336,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
int io_do_iopoll(struct io_ring_ctx * ctx, bool force_nonspin)
```

```json
{
  "name": "io_do_iopoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_do_iopoll",
      "external": true,
      "loc": "io_uring/rw.c:1121",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_iopoll_check",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597544608,
      "name": "io_do_iopoll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587405616,
      "name": "io_do_iopoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493836208,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227342876,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287455384,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273408584,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582229142,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582166950,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582219622,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
  "name": "io_do_iopoll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305287,
      "name": "io_do_iopoll",
      "external": false,
      "loc": "fs/io_uring.c:799",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_iopoll_getevents"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int io_do_iopoll(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool resubmit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool resubmit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_nonspin</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * nr_events</code>
</li>
<li>
<b>Param removed. </b>
<code>long int min</code>
</li>
</ul>
</details>
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
