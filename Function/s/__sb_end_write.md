# Function: <code>__sb_end_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003088,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1224",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_sendfile",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_run_iocb",
        "fs/dax.c:dax_pmd_fault",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_fault",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003088,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161344,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1244",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_run_iocb",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161344,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238048,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1290",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/pipe.c:pipe_write",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_complete",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238048,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285424,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1332",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_complete",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285424,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424816,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1332",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write_file_path",
        "fs/namespace.c:mnt_want_write_file_path",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_complete",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424816,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581840,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1395",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/ioctl.c:ioctl_file_clone",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write_file_path",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581840,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668176,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1381",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668176,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785568,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1537",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785568,
      "name": "__sb_end_write",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857808,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857808,
      "name": "__sb_end_write",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082496,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1636",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_common",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082496,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580310889,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314092,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097299,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124536,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166237,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266364,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280313,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379330,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410732,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537522,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557943,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749794,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019341,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115702,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175154,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297301,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583679995,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221196,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1587",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580314265,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333127,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122099,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149254,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189968,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291692,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305631,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406284,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437532,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566818,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623987,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778440,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045149,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141398,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201698,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321429,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583704619,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109212,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1756",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580467801,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580796,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438931,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466086,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507280,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610492,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624975,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728060,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760316,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883826,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955802,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583105648,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382438,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481930,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544941,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665125,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584065238,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680508,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1806",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_write_bvec"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580661329,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932449,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957998,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986174,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030605,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143443,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583164158,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273639,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311450,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450334,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588100,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895689,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006164,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078629,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234171,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584656401,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585965969,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589031343,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1692",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580931185,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370967,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516286,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546522,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594861,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715411,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583739406,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856023,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583896394,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040990,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192244,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520909,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636286,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711440,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584877730,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585338222,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586855125,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590559755,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1807",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581017598,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575813,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731784,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762501,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811549,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933139,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583956161,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076969,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118336,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584265713,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419788,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483706,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584749757,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859705,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935481,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585104930,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585568164,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121416,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590888256,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1487",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__sb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581113470,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744754,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932583,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965087,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017688,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139454,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:touch_atime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164801,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293120,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335852,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482625,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619644,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/backing-file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/backing-file.c:backing_aio_rw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640605,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706666,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982637,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092633,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167049,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337298,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585806500,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399774,
      "name": "__sb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:1634",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493326960,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493326960,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226923440,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:kiocb_end_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226923440,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286867952,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286867952,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273059092,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273059092,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826544,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826544,
      "name": "__sb_end_write",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764208,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764208,
      "name": "__sb_end_write",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817856,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817856,
      "name": "__sb_end_write",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
```

```json
{
  "name": "__sb_end_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887504,
      "name": "__sb_end_write",
      "external": true,
      "loc": "fs/super.c:1638",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:do_acct_process",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_writev",
        "fs/read_write.c:vfs_writev",
        "fs/pipe.c:pipe_write",
        "fs/inode.c:touch_atime",
        "fs/inode.c:touch_atime",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_drop_write",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_complete_rw",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887504,
      "name": "__sb_end_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __sb_end_write(struct super_block * sb, int level)
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
