# Function: <code>io_install_fixed_file</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_install_fixed_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582938944,
      "name": "io_install_fixed_file",
      "external": false,
      "loc": "fs/io_uring.c:8432",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938944,
      "name": "io_install_fixed_file.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
  "name": "io_install_fixed_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586004439,
      "name": "io_install_fixed_file",
      "external": false,
      "loc": "io_uring/io_uring.c:9707",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_fixed_fd_install"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int io_install_fixed_file(struct io_ring_ctx * ctx, struct file * file, u32 slot_index)
```

```json
{
  "name": "io_install_fixed_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586791168,
      "name": "io_install_fixed_file",
      "external": false,
      "loc": "io_uring/filetable.c:60",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:__io_fixed_fd_install",
        "io_uring/filetable.c:__io_fixed_fd_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586791168,
      "name": "io_install_fixed_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int io_install_fixed_file(struct io_ring_ctx * ctx, struct file * file, u32 slot_index)
```

```json
{
  "name": "io_install_fixed_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587056720,
      "name": "io_install_fixed_file",
      "external": false,
      "loc": "io_uring/filetable.c:63",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:__io_fixed_fd_install",
        "io_uring/filetable.c:__io_fixed_fd_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587056720,
      "name": "io_install_fixed_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int io_install_fixed_file(struct io_ring_ctx * ctx, struct file * file, u32 slot_index)
```

```json
{
  "name": "io_install_fixed_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587334832,
      "name": "io_install_fixed_file",
      "external": false,
      "loc": "io_uring/filetable.c:63",
      "file": "io_uring/filetable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/filetable.c:__io_fixed_fd_install",
        "io_uring/filetable.c:__io_fixed_fd_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334832,
      "name": "io_install_fixed_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int io_install_fixed_file(struct io_ring_ctx * ctx, struct file * file, u32 slot_index)
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
