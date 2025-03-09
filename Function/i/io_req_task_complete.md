# Function: <code>io_req_task_complete</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void io_req_task_complete(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_complete",
      "external": false,
      "loc": "fs/io_uring.c:2713",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949360,
      "name": "io_req_task_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071592238137,
      "name": "io_req_task_complete.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void io_req_task_complete(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585996394,
      "name": "io_req_task_complete",
      "external": false,
      "loc": "io_uring/io_uring.c:3243",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_poll_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990912,
      "name": "io_req_task_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071594120197,
      "name": "io_req_task_complete.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void io_req_task_complete(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586769201,
      "name": "io_req_task_complete",
      "external": true,
      "loc": "io_uring/io_uring.c:1601",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_tw_fail_links",
        "io_uring/poll.c:io_poll_remove",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/rw.c:io_req_rw_complete",
        "io_uring/notif.c:io_notif_complete_tw_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596111331,
      "name": "io_req_task_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586769104,
      "name": "io_req_task_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void io_req_task_complete(struct io_kiocb * req, struct io_tw_state * ts)
```

```json
{
  "name": "io_req_task_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587034641,
      "name": "io_req_task_complete",
      "external": true,
      "loc": "io_uring/io_uring.c:1684",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/uring_cmd.c:io_uring_cmd_done",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_tw_fail_links",
        "io_uring/timeout.c:io_timeout_complete",
        "io_uring/poll.c:io_poll_remove",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/rw.c:io_req_rw_complete",
        "io_uring/notif.c:io_notif_complete_tw_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635666,
      "name": "io_req_task_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587034544,
      "name": "io_req_task_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void io_req_task_complete(struct io_kiocb * req, struct io_tw_state * ts)
```

```json
{
  "name": "io_req_task_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587309393,
      "name": "io_req_task_complete",
      "external": true,
      "loc": "io_uring/io_uring.c:1708",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/uring_cmd.c:io_uring_cmd_done",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_task_link_timeout",
        "io_uring/timeout.c:io_req_tw_fail_links",
        "io_uring/timeout.c:io_timeout_complete",
        "io_uring/poll.c:io_poll_remove",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/poll.c:io_poll_task_func",
        "io_uring/rw.c:io_req_rw_complete",
        "io_uring/notif.c:io_notif_complete_tw_ext",
        "io_uring/waitid.c:io_waitid_complete",
        "io_uring/futex.c:io_futexv_complete",
        "io_uring/futex.c:io_futex_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597543368,
      "name": "io_req_task_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587309296,
      "name": "io_req_task_complete",
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
void io_req_task_complete(struct io_kiocb * req, bool * locked)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_tw_state * ts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool * locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
