# Function: <code>revert_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509088,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:549",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509088,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523344,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:549",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:SyS_access",
        "fs/namei.c:follow_managed",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523344,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546992,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:549",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546992,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533616,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:550",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533616,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560112,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:550",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:SyS_access",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560112,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588144,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:550",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588144,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625600,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:552",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625600,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650224,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650224,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687360,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687360,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727440,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:585",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io-wq.c:__io_worker_unuse",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727440,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706448,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:585",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io-wq.c:__io_worker_unuse",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706448,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713584,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:597",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713584,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791792,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:595",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791792,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898912,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:595",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io_uring.c:io_issue_sqe",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898912,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050864,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:595",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/sqpoll.c:io_sq_thread",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050864,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105312,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:595",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/coredump.c:do_coredump",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/sqpoll.c:io_sq_thread",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105312,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150224,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:517",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/trace/trace_events_user.c:user_event_set_call_visible",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/backing-file.c:backing_file_mmap",
        "fs/backing-file.c:backing_file_splice_read",
        "fs/coredump.c:do_coredump",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/sqpoll.c:io_sq_thread",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150224,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490864064,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490864064,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224883160,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224883160,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283694848,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283694848,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271520596,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271520596,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663680,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663680,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592032,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592032,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660944,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660944,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void revert_creds(const struct cred * old)
```

```json
{
  "name": "revert_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579694944,
      "name": "revert_creds",
      "external": true,
      "loc": "kernel/cred.c:582",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694944,
      "name": "revert_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
