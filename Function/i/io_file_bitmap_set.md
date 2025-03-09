# Function: <code>io_file_bitmap_set</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_file_bitmap_set(struct io_file_table * table, int bit)
```

```json
{
  "name": "io_file_bitmap_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586007610,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/io_uring.c:9243",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_fixed_fd_install"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946480,
      "name": "io_file_bitmap_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_file_bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586791463,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:33",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848387,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:33",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update"
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
  "name": "io_file_bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056952,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:29",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115003,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:29",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update"
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
  "name": "io_file_bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587335000,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:29",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393749,
      "name": "io_file_bitmap_set",
      "external": false,
      "loc": "io_uring/filetable.h:29",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:__io_sqe_files_update"
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
void io_file_bitmap_set(struct io_file_table * table, int bit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void io_file_bitmap_set(struct io_file_table * table, int bit)
```
</details>
</li>
</ul>
