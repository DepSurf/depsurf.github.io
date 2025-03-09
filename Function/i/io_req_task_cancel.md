# Function: <code>io_req_task_cancel</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void io_req_task_cancel(struct callback_head * cb)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590128,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "fs/io_uring.c:2200",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590128,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void io_req_task_cancel(struct callback_head * cb)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604496,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "fs/io_uring.c:2045",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604496,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void io_req_task_cancel(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "fs/io_uring.c:2270",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949024,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071592238116,
      "name": "io_req_task_cancel.cold",
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
void io_req_task_cancel(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:2834",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989664,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071594120155,
      "name": "io_req_task_cancel.cold",
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
void io_req_task_cancel(struct io_kiocb * req, bool * locked)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:1364",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765376,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071596111310,
      "name": "io_req_task_cancel.cold",
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
void io_req_task_cancel(struct io_kiocb * req, struct io_tw_state * ts)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:1470",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034960,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071596635687,
      "name": "io_req_task_cancel.cold",
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
void io_req_task_cancel(struct io_kiocb * req, struct io_tw_state * ts)
```

```json
{
  "name": "io_req_task_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_req_task_cancel",
      "external": false,
      "loc": "io_uring/io_uring.c:1491",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309712,
      "name": "io_req_task_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071597543389,
      "name": "io_req_task_cancel.cold",
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void io_req_task_cancel(struct callback_head * cb)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_kiocb * req</code>
</li>
<li>
<b>Param added. </b>
<code>bool * locked</code>
</li>
<li>
<b>Param removed. </b>
<code>struct callback_head * cb</code>
</li>
</ul>
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
