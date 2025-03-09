# Function: <code>io_issue_sqe</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int io_issue_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool force_nonblock)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544128,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:5274",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544128,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4426
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
int io_issue_sqe(struct io_kiocb * req, bool force_nonblock, struct io_comp_state * cs)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613920,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6263",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613920,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2599
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
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642400,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6139",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642400,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4715
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
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6700",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_wq_submit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960448,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4809
    },
    {
      "addr": 18446744071592238257,
      "name": "io_issue_sqe.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:8018",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_poll_check_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978880,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    },
    {
      "addr": 18446744071594117960,
      "name": "io_issue_sqe.cold",
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
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:1842",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_poll_issue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777728,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1030
    },
    {
      "addr": 18446744071596111493,
      "name": "io_issue_sqe.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:1854",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_poll_issue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045264,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    },
    {
      "addr": 18446744071596635850,
      "name": "io_issue_sqe.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int io_issue_sqe(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_issue_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_issue_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:1878",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_poll_issue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587320496,
      "name": "io_issue_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071597543552,
      "name": "io_issue_sqe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int io_issue_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe, bool force_nonblock)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_comp_state * cs</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, sqe, force_nonblock</code> ➡️ <code>req, force_nonblock, cs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_nonblock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state * cs</code>
</li>
</ul>
</details>
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
