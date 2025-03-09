# Function: <code>kiocb_done</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kiocb_done(struct kiocb * kiocb, ssize_t ret)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526896,
      "name": "kiocb_done",
      "external": false,
      "loc": "fs/io_uring.c:2232",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526896,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void kiocb_done(struct kiocb * kiocb, ssize_t ret, struct io_comp_state * cs)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611520,
      "name": "kiocb_done",
      "external": false,
      "loc": "fs/io_uring.c:2979",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611520,
      "name": "kiocb_done",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void kiocb_done(struct kiocb * kiocb, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624144,
      "name": "kiocb_done",
      "external": false,
      "loc": "fs/io_uring.c:2759",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624144,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void kiocb_done(struct kiocb * kiocb, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955136,
      "name": "kiocb_done",
      "external": false,
      "loc": "fs/io_uring.c:2978",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955136,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
void kiocb_done(struct io_kiocb * req, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009792,
      "name": "kiocb_done",
      "external": false,
      "loc": "io_uring/io_uring.c:3484",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009792,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
int kiocb_done(struct io_kiocb * req, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855936,
      "name": "kiocb_done",
      "external": false,
      "loc": "io_uring/rw.c:329",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855936,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int kiocb_done(struct io_kiocb * req, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587122272,
      "name": "kiocb_done",
      "external": false,
      "loc": "io_uring/rw.c:329",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122272,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int kiocb_done(struct io_kiocb * req, ssize_t ret, unsigned int issue_flags)
```

```json
{
  "name": "kiocb_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402080,
      "name": "kiocb_done",
      "external": false,
      "loc": "io_uring/rw.c:381",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402080,
      "name": "kiocb_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
void kiocb_done(struct kiocb * kiocb, ssize_t ret)
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
<code>struct io_comp_state * cs</code>
</li>
</ul>
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
<code>struct io_kiocb * req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb * kiocb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
