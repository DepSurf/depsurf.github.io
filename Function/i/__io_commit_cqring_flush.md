# Function: <code>__io_commit_cqring_flush</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_commit_cqring_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928112,
      "name": "__io_commit_cqring_flush",
      "external": false,
      "loc": "fs/io_uring.c:1578",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_rsrc_put_work",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:__io_req_find_next",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:__io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928112,
      "name": "__io_commit_cqring_flush",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_commit_cqring_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_commit_cqring_flush",
      "external": false,
      "loc": "io_uring/io_uring.c:1955",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_rsrc_put_work",
        "io_uring/io_uring.c:io_poll_task_func",
        "io_uring/io_uring.c:io_poll_check_events",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_msg_ring",
        "io_uring/io_uring.c:io_do_iopoll",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "io_uring/io_uring.c:handle_prev_tw_list",
        "io_uring/io_uring.c:io_req_complete_post",
        "io_uring/io_uring.c:__io_cqring_overflow_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966064,
      "name": "__io_commit_cqring_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071594113908,
      "name": "__io_commit_cqring_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_commit_cqring_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766736,
      "name": "__io_commit_cqring_flush",
      "external": true,
      "loc": "io_uring/io_uring.c:573",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_aux_cqe",
        "io_uring/io_uring.c:io_cq_unlock_post",
        "io_uring/rw.c:io_do_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766736,
      "name": "__io_commit_cqring_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_commit_cqring_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030160,
      "name": "__io_commit_cqring_flush",
      "external": true,
      "loc": "io_uring/io_uring.c:611",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_aux_cqe",
        "io_uring/io_uring.c:io_aux_cqe",
        "io_uring/io_uring.c:io_cq_unlock_post",
        "io_uring/rw.c:io_do_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030160,
      "name": "__io_commit_cqring_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```

```json
{
  "name": "__io_commit_cqring_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305280,
      "name": "__io_commit_cqring_flush",
      "external": true,
      "loc": "io_uring/io_uring.c:624",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:io_fill_cqe_req_aux",
        "io_uring/io_uring.c:io_cq_unlock_post"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305280,
      "name": "__io_commit_cqring_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __io_commit_cqring_flush(struct io_ring_ctx * ctx)
```
</details>
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
