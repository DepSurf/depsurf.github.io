# Function: <code>io_fixed_fd_install</code>

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
int io_fixed_fd_install(struct io_kiocb * req, unsigned int issue_flags, struct file * file, unsigned int file_slot)
```

```json
{
  "name": "io_fixed_fd_install",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586004368,
      "name": "io_fixed_fd_install",
      "external": false,
      "loc": "io_uring/io_uring.c:5211",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_files_update",
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_openat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586004368,
      "name": "io_fixed_fd_install",
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
int io_fixed_fd_install(struct io_kiocb * req, unsigned int issue_flags, struct file * file, unsigned int file_slot)
```

```json
{
  "name": "io_fixed_fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792032,
      "name": "io_fixed_fd_install",
      "external": true,
      "loc": "io_uring/filetable.c:131",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792032,
      "name": "io_fixed_fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int io_fixed_fd_install(struct io_kiocb * req, unsigned int issue_flags, struct file * file, unsigned int file_slot)
```

```json
{
  "name": "io_fixed_fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587057488,
      "name": "io_fixed_fd_install",
      "external": true,
      "loc": "io_uring/filetable.c:123",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057488,
      "name": "io_fixed_fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int io_fixed_fd_install(struct io_kiocb * req, unsigned int issue_flags, struct file * file, unsigned int file_slot)
```

```json
{
  "name": "io_fixed_fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587335584,
      "name": "io_fixed_fd_install",
      "external": true,
      "loc": "io_uring/filetable.c:120",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "io_uring/rsrc.c:io_files_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587335584,
      "name": "io_fixed_fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int io_fixed_fd_install(struct io_kiocb * req, unsigned int issue_flags, struct file * file, unsigned int file_slot)
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
