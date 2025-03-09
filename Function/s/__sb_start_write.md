# Function: <code>__sb_start_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581005056,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1234",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_run_iocb",
        "fs/dax.c:dax_pmd_fault",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:dax_fault",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005056,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163312,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1254",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_run_iocb",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163312,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581240272,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1300",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_pfn_mkwrite",
        "fs/ext4/file.c:ext4_dax_pmd_fault",
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240272,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581287648,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1342",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287648,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581427184,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1342",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/namespace.c:mnt_want_write_file_path",
        "fs/splice.c:SyS_splice",
        "fs/aio.c:aio_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427184,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582064,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1405",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/namespace.c:mnt_want_write_file_path",
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582064,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581668400,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1391",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668400,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785792,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1547",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785792,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581858064,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858064,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582082752,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1646",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_sample_last_mounted",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082752,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313984,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097394,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124788,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
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
      "addr": 18446744071582290131,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379363,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410688,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528056,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613106,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749827,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583023403,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115580,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175016,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583679964,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221164,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1592",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333024,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122194,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149589,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
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
      "addr": 18446744071582317267,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406317,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437488,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556864,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636238,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778868,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049069,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141276,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201560,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704588,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109180,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1761",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581580688,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439042,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466453,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
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
      "addr": 18446744071582637619,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728093,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760272,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582873040,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957807,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106076,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386676,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481804,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544763,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065207,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680476,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1811",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932321,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958153,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986452,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
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
      "addr": 18446744071583174195,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273697,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311378,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437365,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588036,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583900678,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006016,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078411,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584656345,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586018920,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589031273,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1697",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582370779,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516441,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546818,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
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
      "addr": 18446744071583749203,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856081,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583896322,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584027077,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192339,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526163,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636141,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711227,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585338166,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859715,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559685,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1812",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582575630,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731958,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762825,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
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
      "addr": 18446744071583965747,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077031,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118264,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584253246,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419883,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483657,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755209,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859556,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935426,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568108,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125958,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590888087,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1492",
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
  "name": "__sb_start_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582744574,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932744,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_ftruncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965514,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
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
      "addr": 18446744071584165651,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mnt_want_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293178,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335914,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470462,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619313,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/backing-file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640700,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706617,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quotactl_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987945,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092484,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166994,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806444,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "fs/fuse/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dax.c:__fuse_dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587405184,
      "name": "__sb_start_write",
      "external": false,
      "loc": "include/linux/fs.h:1639",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493327064,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493327064,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226926392,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226926392,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286872832,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286872832,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273059528,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273059528,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581826800,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826800,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764464,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764464,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581818112,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818112,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __sb_start_write(struct super_block * sb, int level, bool wait)
```

```json
{
  "name": "__sb_start_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581890128,
      "name": "__sb_start_write",
      "external": true,
      "loc": "fs/super.c:1648",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
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
        "fs/splice.c:do_splice",
        "fs/aio.c:aio_write",
        "fs/io_uring.c:io_write",
        "fs/coredump.c:do_coredump",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mmp.c:write_mmp_block",
        "drivers/block/loop.c:lo_write_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890128,
      "name": "__sb_start_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __sb_start_write(struct super_block * sb, int level, bool wait)
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
