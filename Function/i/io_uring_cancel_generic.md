# Function: <code>io_uring_cancel_generic</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```

```json
{
  "name": "io_uring_cancel_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_cancel_generic",
      "external": false,
      "loc": "fs/io_uring.c:9806",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_uring_cancel",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975456,
      "name": "io_uring_cancel_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071592238444,
      "name": "io_uring_cancel_generic.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```

```json
{
  "name": "io_uring_cancel_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594125760,
      "name": "io_uring_cancel_generic",
      "external": false,
      "loc": "io_uring/io_uring.c:11196",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_cancel",
        "io_uring/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594125760,
      "name": "io_uring_cancel_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```

```json
{
  "name": "io_uring_cancel_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586784496,
      "name": "io_uring_cancel_generic",
      "external": true,
      "loc": "io_uring/io_uring.c:3089",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_cancel",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586784496,
      "name": "io_uring_cancel_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```

```json
{
  "name": "io_uring_cancel_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587049968,
      "name": "io_uring_cancel_generic",
      "external": true,
      "loc": "io_uring/io_uring.c:3311",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_cancel",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587049968,
      "name": "io_uring_cancel_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```

```json
{
  "name": "io_uring_cancel_generic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328000,
      "name": "io_uring_cancel_generic",
      "external": true,
      "loc": "io_uring/io_uring.c:3332",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_cancel",
        "io_uring/sqpoll.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328000,
      "name": "io_uring_cancel_generic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data * sqd)
```
</details>
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
