# Function: <code>io_run_task_work</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_run_task_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582551906,
      "name": "io_run_task_work",
      "external": false,
      "loc": "fs/io_uring.c:1763",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_run_task_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582622432,
      "name": "io_run_task_work",
      "external": false,
      "loc": "fs/io_uring.c:2416",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_iopoll_check",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582641763,
      "name": "io_run_task_work",
      "external": false,
      "loc": "fs/io_uring.c:2255",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait"
      ],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582587968,
      "name": "io_run_task_work",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582970179,
      "name": "io_run_task_work",
      "external": false,
      "loc": "fs/io_uring.c:2467",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": [
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905520,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586024496,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.c:2994",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io_uring.c:io_sq_thread"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960720,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586752544,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:265",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    },
    {
      "addr": 18446744071586816528,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:265",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    },
    {
      "addr": 18446744071586863344,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:265",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752544,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071586816528,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071586863344,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587017232,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:274",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_run_task_work_sig",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    },
    {
      "addr": 18446744071587082864,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:274",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    },
    {
      "addr": 18446744071587129520,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:274",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017232,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587082864,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587129520,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int io_run_task_work()
```

```json
{
  "name": "io_run_task_work",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587297200,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:275",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_try_cancel_requests",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_run_task_work_sig",
        "io_uring/io_uring.c:io_iopoll_check"
      ]
    },
    {
      "addr": 18446744071587362192,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:275",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    },
    {
      "addr": 18446744071587415664,
      "name": "io_run_task_work",
      "external": false,
      "loc": "io_uring/io_uring.h:275",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io-wq.c:io_wq_worker",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297200,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587362192,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587415664,
      "name": "io_run_task_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool io_run_task_work()
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
