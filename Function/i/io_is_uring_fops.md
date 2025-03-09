# Function: <code>io_is_uring_fops</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_is_uring_fops(struct file * file)
```

```json
{
  "name": "io_is_uring_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586760682,
      "name": "io_is_uring_fops",
      "external": true,
      "loc": "io_uring/io_uring.c:3431",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_file_get_flags",
        "io_uring/io_uring.c:io_uring_get_socket"
      ],
      "caller_func": [
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/openclose.c:io_close",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586785280,
      "name": "io_is_uring_fops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool io_is_uring_fops(struct file * file)
```

```json
{
  "name": "io_is_uring_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587027613,
      "name": "io_is_uring_fops",
      "external": true,
      "loc": "io_uring/io_uring.c:3717",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_uring_get_socket"
      ],
      "caller_func": [
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/openclose.c:io_close",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050864,
      "name": "io_is_uring_fops",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool io_is_uring_fops(struct file * file)
```

```json
{
  "name": "io_is_uring_fops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587324108,
      "name": "io_is_uring_fops",
      "external": true,
      "loc": "io_uring/io_uring.c:3740",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_file_get_normal"
      ],
      "caller_func": [
        "io_uring/filetable.c:io_install_fixed_file",
        "io_uring/openclose.c:io_close",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/sqpoll.c:io_sq_offload_create",
        "io_uring/sqpoll.c:io_get_sq_data",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/register.c:__do_sys_io_uring_register",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328896,
      "name": "io_is_uring_fops",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool io_is_uring_fops(struct file * file)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
