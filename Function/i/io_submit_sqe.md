# Function: <code>io_submit_sqe</code>

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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187152,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2124",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187152,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266880,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266880,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int io_submit_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549776,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:5859",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549776,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int io_submit_sqe(struct io_kiocb * req, const struct io_uring_sqe * sqe, struct io_submit_link * link, struct io_comp_state * cs)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618560,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6670",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618560,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
int io_submit_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648192,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:6598",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648192,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int io_submit_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, const struct io_uring_sqe * sqe)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971456,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:7175",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971456,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586013655,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:8502",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780768,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2240",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047667,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2265",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587322905,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "io_uring/io_uring.c:2293",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493847336,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493847336,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227340700,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227340700,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287463264,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287463264,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273413230,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273413230,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235616,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235616,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173376,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173376,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226096,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226096,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
```

```json
{
  "name": "io_submit_sqe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303200,
      "name": "io_submit_sqe",
      "external": false,
      "loc": "fs/io_uring.c:2510",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303200,
      "name": "io_submit_sqe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
void io_submit_sqe(struct io_ring_ctx * ctx, struct sqe_submit * s, struct io_submit_state * state, struct io_kiocb * * link)
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
<b>Param added. </b>
<code>struct io_kiocb * req</code>
</li>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe * sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sqe_submit * s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_submit_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, s, state, link</code> ➡️ <code>req, sqe, link</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
<b>Param type changed. </b>
<code>struct io_kiocb * * link</code> ➡️ <code>struct io_submit_link * link</code>
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
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_submit_link * link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state * cs</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, sqe, link, cs</code> ➡️ <code>ctx, req, sqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int io_submit_sqe(struct io_ring_ctx * ctx, struct io_kiocb * req, const struct io_uring_sqe * sqe)
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
