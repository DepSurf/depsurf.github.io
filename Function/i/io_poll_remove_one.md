# Function: <code>io_poll_remove_one</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182592,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1530",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182592,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260112,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260112,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
bool io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524000,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:4599",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_remove_link",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524000,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
bool io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585744,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:5529",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_poll_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585744,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582611793,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:5275",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_poll_remove_all"
      ],
      "caller_func": [
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_async_cancel",
        "fs/io_uring.c:io_poll_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596320,
      "name": "io_poll_remove_one.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582931888,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:5733",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_try_cancel_userdata",
        "fs/io_uring.c:io_poll_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582931888,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493831000,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493831000,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227332956,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227332956,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287451360,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287451360,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273409284,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273409284,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228848,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228848,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582166656,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166656,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219328,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219328,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void io_poll_remove_one(struct io_kiocb * req)
```

```json
{
  "name": "io_poll_remove_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295920,
      "name": "io_poll_remove_one",
      "external": false,
      "loc": "fs/io_uring.c:1711",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295920,
      "name": "io_poll_remove_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void io_poll_remove_one(struct io_kiocb * req)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool io_poll_remove_one(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool io_poll_remove_one(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool io_poll_remove_one(struct io_kiocb * req)
```
</details>
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
