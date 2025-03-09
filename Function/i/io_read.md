# Function: <code>io_read</code>

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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177872,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1229",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177872,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256016,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256016,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int io_read(struct io_kiocb * req, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527040,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:2660",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527040,
      "name": "io_read",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int io_read(struct io_kiocb * req, bool force_nonblock, struct io_comp_state * cs)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611712,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:3494",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611712,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636416,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:3273",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636416,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956016,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:3504",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956016,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586019136,
      "name": "io_read",
      "external": false,
      "loc": "io_uring/io_uring.c:4096",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019136,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1243
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586857632,
      "name": "io_read",
      "external": true,
      "loc": "io_uring/rw.c:702",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857632,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1272
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123872,
      "name": "io_read",
      "external": true,
      "loc": "io_uring/rw.c:704",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123872,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
int io_read(struct io_kiocb * req, unsigned int issue_flags)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403968,
      "name": "io_read",
      "external": true,
      "loc": "io_uring/rw.c:913",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587403968,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493829024,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493829024,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227331184,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227331184,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287449072,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287449072,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273404324,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273404324,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224752,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224752,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162592,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162592,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215232,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215232,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
```

```json
{
  "name": "io_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582293248,
      "name": "io_read",
      "external": false,
      "loc": "fs/io_uring.c:1388",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293248,
      "name": "io_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
int io_read(struct io_kiocb * req, const struct sqe_submit * s, bool force_nonblock)
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
<b>Param removed. </b>
<code>const struct sqe_submit * s</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, s, force_nonblock</code> ➡️ <code>req, force_nonblock</code>
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
