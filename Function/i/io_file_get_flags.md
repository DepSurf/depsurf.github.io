# Function: <code>io_file_get_flags</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int io_file_get_flags(struct file * file)
```

```json
{
  "name": "io_file_get_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585952688,
      "name": "io_file_get_flags",
      "external": false,
      "loc": "io_uring/io_uring.c:3388",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_sqe_files_register",
        "io_uring/io_uring.c:io_fixed_fd_install",
        "io_uring/io_uring.c:io_rw_init_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952688,
      "name": "io_file_get_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
unsigned int io_file_get_flags(struct file * file)
```

```json
{
  "name": "io_file_get_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586775024,
      "name": "io_file_get_flags",
      "external": true,
      "loc": "io_uring/io_uring.c:1703",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_prep_async_work",
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/rw.c:io_rw_init_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586775024,
      "name": "io_file_get_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int io_file_get_flags(struct file * file)
```

```json
{
  "name": "io_file_get_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018937,
      "name": "io_file_get_flags",
      "external": true,
      "loc": "io_uring/io_uring.c:1747",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": [
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/rw.c:io_rw_init_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043664,
      "name": "io_file_get_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int io_file_get_flags(struct file * file)
```

```json
{
  "name": "io_file_get_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298733,
      "name": "io_file_get_flags",
      "external": true,
      "loc": "io_uring/io_uring.c:1771",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_prep_async_work"
      ],
      "caller_func": [
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/rw.c:io_rw_init_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318896,
      "name": "io_file_get_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
unsigned int io_file_get_flags(struct file * file)
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
