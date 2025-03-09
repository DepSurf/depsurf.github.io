# Function: <code>backing_file_real_path</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct path * backing_file_real_path(struct file * f)
```

```json
{
  "name": "backing_file_real_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583764650,
      "name": "backing_file_real_path",
      "external": true,
      "loc": "fs/file_table.c:58",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput",
        "fs/file_table.c:__fput"
      ],
      "caller_func": [
        "fs/open.c:backing_file_open",
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763984,
      "name": "backing_file_real_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct path * backing_file_real_path(struct file * f)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct path * backing_file_real_path(struct file * f)
```
</details>
</li>
</ul>
