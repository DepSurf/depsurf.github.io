# Function: <code>override_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508384,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
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
      "addr": 18446744071579508384,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579522640,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
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
      "addr": 18446744071579522640,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546288,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
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
      "addr": 18446744071579546288,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532912,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:521",
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
      "addr": 18446744071579532912,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559408,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:521",
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
      "addr": 18446744071579559408,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587680,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:521",
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
      "addr": 18446744071579587680,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624880,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:523",
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
      "addr": 18446744071579624880,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649488,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579649488,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686624,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579686624,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726720,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:544",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:access_override_creds",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726720,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705664,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:544",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:access_override_creds",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io-wq.c:io_impersonate_work",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705664,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712800,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:556",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "fs/open.c:do_faccessat",
        "fs/aio.c:aio_fsync_work",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712800,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791008,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:554",
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
        "fs/coredump.c:do_coredump",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791008,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897936,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:554",
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
      "addr": 18446744071579897936,
      "name": "override_creds",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049728,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:554",
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
      "addr": 18446744071580049728,
      "name": "override_creds",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104176,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:554",
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
      "addr": 18446744071580104176,
      "name": "override_creds",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149072,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:486",
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
      "addr": 18446744071580149072,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490864296,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446603336490864296,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224882028,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 3224882028,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283693568,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 13835058055283693568,
      "name": "override_creds",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271520214,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446743936271520214,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662944,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579662944,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591296,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579591296,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660208,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579660208,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const struct cred * override_creds(const struct cred * new)
```

```json
{
  "name": "override_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579694192,
      "name": "override_creds",
      "external": true,
      "loc": "kernel/cred.c:541",
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
      "addr": 18446744071579694192,
      "name": "override_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
