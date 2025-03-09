# Function: <code>io_ring_ctx_free</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582182899,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3063",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271692,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535744,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:7456",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535744,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579200,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:8687",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579200,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624624,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:8624",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624624,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929136,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:9327",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929136,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1301
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594119271,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "io_uring/io_uring.c:10704",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594119271,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756800,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "io_uring/io_uring.c:2708",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756800,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 847
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023456,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "io_uring/io_uring.c:2865",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023456,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
void io_ring_ctx_free(struct io_ring_ctx * ctx)
```

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587303872,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "io_uring/io_uring.c:2876",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_ring_exit_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587303872,
      "name": "io_ring_ctx_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493837456,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227345268,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287469404,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273417404,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582240428,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582178160,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582230908,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_ring_ctx_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309165,
      "name": "io_ring_ctx_free",
      "external": false,
      "loc": "fs/io_uring.c:3616",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx * ctx)
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
