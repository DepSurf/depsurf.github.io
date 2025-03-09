# Function: <code>io_cqring_event_overflow</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, long int res, unsigned int cflags)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588224,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "fs/io_uring.c:1548",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588224,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, long int res, unsigned int cflags)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901856,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "fs/io_uring.c:1775",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901856,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970176,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "io_uring/io_uring.c:2205",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_fill_cqe_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970176,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586752976,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "io_uring/io_uring.c:727",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes",
        "io_uring/io_uring.c:__io_flush_post_cqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752976,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587017840,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "io_uring/io_uring.c:777",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes",
        "io_uring/io_uring.c:__io_flush_post_cqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017840,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, s32 res, u32 cflags, u64 extra1, u64 extra2)
```

```json
{
  "name": "io_cqring_event_overflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587297632,
      "name": "io_cqring_event_overflow",
      "external": false,
      "loc": "io_uring/io_uring.c:785",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_post_aux_cqe",
        "io_uring/io_uring.c:__io_flush_post_cqes",
        "io_uring/io_uring.c:__io_flush_post_cqes",
        "io_uring/io_uring.c:io_req_cqe_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297632,
      "name": "io_cqring_event_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
bool io_cqring_event_overflow(struct io_ring_ctx * ctx, u64 user_data, long int res, unsigned int cflags)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 extra2</code>
</li>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>s32 res</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int cflags</code> ➡️ <code>u32 cflags</code>
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
