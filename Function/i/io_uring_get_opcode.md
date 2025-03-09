# Function: <code>io_uring_get_opcode</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * io_uring_get_opcode(u8 opcode)
```

```json
{
  "name": "io_uring_get_opcode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585965460,
      "name": "io_uring_get_opcode",
      "external": true,
      "loc": "io_uring/io_uring.c:1162",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025184,
      "name": "io_uring_get_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
const char * io_uring_get_opcode(u8 opcode)
```

```json
{
  "name": "io_uring_get_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586860976,
      "name": "io_uring_get_opcode",
      "external": true,
      "loc": "io_uring/opdef.c:537",
      "file": "io_uring/opdef.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_sqe",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/fdinfo.c:__io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860976,
      "name": "io_uring_get_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
const char * io_uring_get_opcode(u8 opcode)
```

```json
{
  "name": "io_uring_get_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587127168,
      "name": "io_uring_get_opcode",
      "external": true,
      "loc": "io_uring/opdef.c:653",
      "file": "io_uring/opdef.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/fdinfo.c:__io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127168,
      "name": "io_uring_get_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const char * io_uring_get_opcode(u8 opcode)
```

```json
{
  "name": "io_uring_get_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587406240,
      "name": "io_uring_get_opcode",
      "external": true,
      "loc": "io_uring/opdef.c:717",
      "file": "io_uring/opdef.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_task_add",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_poll_arm",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_submit_req",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_defer",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:perf_trace_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_defer",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work",
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406240,
      "name": "io_uring_get_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
const char * io_uring_get_opcode(u8 opcode)
```
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
