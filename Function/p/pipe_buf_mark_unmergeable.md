# Function: <code>pipe_buf_mark_unmergeable</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701312,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:253",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701312,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819152,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819152,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891712,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891712,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493369704,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493369704,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226956956,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226956956,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286917072,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286917072,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273089022,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273089022,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860448,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860448,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798048,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798048,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851760,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851760,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```

```json
{
  "name": "pipe_buf_mark_unmergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921264,
      "name": "pipe_buf_mark_unmergeable",
      "external": true,
      "loc": "fs/pipe.c:260",
      "file": "fs/pipe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921264,
      "name": "pipe_buf_mark_unmergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer * buf)
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
