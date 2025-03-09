# Function: <code>io_fixed_file_set</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void io_fixed_file_set(struct io_fixed_file * file_slot, struct file * file)
```

```json
{
  "name": "io_fixed_file_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582816,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "fs/io_uring.c:6338",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582816,
      "name": "io_fixed_file_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void io_fixed_file_set(struct io_fixed_file * file_slot, struct file * file)
```

```json
{
  "name": "io_fixed_file_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582899664,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "fs/io_uring.c:6896",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899664,
      "name": "io_fixed_file_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "io_fixed_file_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586007589,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/io_uring.c:8136",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_sqe_files_register",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_fixed_file_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586791450,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:54",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848366,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:54",
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
  "name": "io_fixed_file_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056938,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:62",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587114985,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:62",
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
  "name": "io_fixed_file_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587334982,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:62",
      "file": "io_uring/filetable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/filetable.c:io_install_fixed_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393727,
      "name": "io_fixed_file_set",
      "external": false,
      "loc": "io_uring/filetable.h:62",
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void io_fixed_file_set(struct io_fixed_file * file_slot, struct file * file)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void io_fixed_file_set(struct io_fixed_file * file_slot, struct file * file)
```
</details>
</li>
</ul>
