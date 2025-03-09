# Function: <code>__get_task_ioprio</code>

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
int __get_task_ioprio(struct task_struct * p)
```

```json
{
  "name": "__get_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586523792,
      "name": "__get_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:148",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "fs/read_write.c:do_iter_readv_writev",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/seq_file.c:seq_read",
        "fs/splice.c:generic_file_splice_read",
        "fs/aio.c:aio_prep_rw",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_get",
        "io_uring/rw.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523792,
      "name": "__get_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __get_task_ioprio(struct task_struct * p)
```

```json
{
  "name": "__get_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586770000,
      "name": "__get_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:149",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_splice_read",
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "fs/read_write.c:do_iter_readv_writev",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/seq_file.c:seq_read",
        "fs/splice.c:copy_splice_read",
        "fs/aio.c:aio_prep_rw",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_get",
        "io_uring/rw.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770000,
      "name": "__get_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__get_task_ioprio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582761297,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450507,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:swap_writepage_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945496,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_readv_writev",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584206437,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584286713,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:copy_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584467377,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_prep_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586924229,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587042654,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402844,
      "name": "__get_task_ioprio",
      "external": false,
      "loc": "include/linux/ioprio.h:57",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_prep_rw"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __get_task_ioprio(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __get_task_ioprio(struct task_struct * p)
```
</details>
</li>
</ul>
