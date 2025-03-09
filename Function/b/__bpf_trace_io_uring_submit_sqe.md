# Function: <code>__bpf_trace_io_uring_submit_sqe</code>

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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493936,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:331",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493936,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552000,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:331",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552000,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580944,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:334",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580944,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, void * req, u8 opcode, u64 user_data, u32 flags, bool force_nonblock, bool sq_thread)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898576,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:335",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898576,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, void * req, long long unsigned int user_data, u8 opcode, u32 flags, bool force_nonblock, bool sq_thread)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585951968,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:390",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951968,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void __bpf_trace_io_uring_submit_sqe(void * __data, struct io_kiocb * req, bool force_nonblock)
```

```json
{
  "name": "__bpf_trace_io_uring_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586743504,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "external": false,
      "loc": "include/trace/events/io_uring.h:371",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743504,
      "name": "__bpf_trace_io_uring_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void __bpf_trace_io_uring_submit_sqe(void * __data, void * ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<code>void * req</code>
</li>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, user_data, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code>
</li>
<li>
<b>Param type changed. </b>
<code>u64 user_data</code> ➡️ <code>long long unsigned int user_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int user_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sq_thread</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, req, force_nonblock</code>
</li>
<li>
<b>Param type changed. </b>
<code>void * req</code> ➡️ <code>struct io_kiocb * req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void * __data, struct io_kiocb * req, bool force_nonblock)
```
</details>
</li>
</ul>
