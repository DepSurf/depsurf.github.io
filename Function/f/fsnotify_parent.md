# Function: <code>fsnotify_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580981043,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992326,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000857,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016523,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074525,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090429,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112393,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147532,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402048,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515644,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_notify_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971111,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239312,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:29",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_permission",
        "security/security.c:security_file_open"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581144348,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146852,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159097,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174927,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237064,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255977,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278028,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314593,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_removexattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580289,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183333,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463861,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581219545,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225638,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235821,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251909,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314956,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333785,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356417,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394668,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665226,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272760,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556330,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581266680,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271921,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282973,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301390,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366666,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389417,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411754,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449950,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719640,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357331,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643370,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:20",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581405816,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410871,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422493,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441377,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508108,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529617,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581553360,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591934,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864776,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508131,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797856,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581560497,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566566,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580586,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600067,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664842,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683337,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709505,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750874,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045597,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699159,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995051,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581645668,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650453,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665760,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686029,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751211,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769961,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796018,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837402,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134686,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582802493,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583106726,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:21",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581762413,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767731,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782884,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804263,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868589,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914852,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961689,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582296977,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582976982,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583293021,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581834621,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850144,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855108,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876727,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940989,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987233,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034441,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582395769,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083190,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398150,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410928,
      "name": "fsnotify_parent",
      "external": true,
      "loc": "fs/notify/fsnotify.c:146",
      "file": "fs/notify/fsnotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/readdir.c:iterate_dir",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410928,
      "name": "fsnotify_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582104899,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124632,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127132,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155269,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218701,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268402,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317217,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410321,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582591141,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_openat2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752105,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517392,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858026,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
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
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582129843,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149384,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151100,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582179625,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245165,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293866,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344649,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437114,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605689,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_openat2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781129,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540350,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583884189,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:51",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582446479,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466212,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468679,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497048,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582562989,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612737,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665481,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759862,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953787,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_openat2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108992,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583898334,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241323,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "security/security.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582965186,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985921,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988354,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583023538,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092746,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583145508,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204960,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310934,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590751,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584474973,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584847932,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586005736,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_fallocate",
        "io_uring/io_uring.c:__io_complete_rw_common",
        "io_uring/io_uring.c:__io_complete_rw_common"
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
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583524162,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_openat2",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546581,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548950,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587362,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660714,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719065,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783808,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895862,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178296,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195263,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139027,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550588,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586790585,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "io_uring/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sync.c:io_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586793432,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "io_uring/openclose.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/openclose.c:io_openat2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586855439,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
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
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583729684,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762578,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583764677,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583877786,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936074,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998928,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584079560,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117697,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584406031,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368134,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781284,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587056107,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "io_uring/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sync.c:io_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587121751,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
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
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583930624,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965237,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv",
        "fs/read_write.c:vfs_iter_write",
        "fs/read_write.c:vfs_iocb_iter_write",
        "fs/read_write.c:vfs_iter_read",
        "fs/read_write.c:vfs_iocb_iter_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:rw_verify_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967752,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085462,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584142332,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584211568,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295585,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335984,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/remap_range.c:vfs_clone_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584626751,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585602870,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586040560,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334220,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
      "file": "io_uring/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sync.c:io_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401469,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:57",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493297932,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493316404,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493323624,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493355180,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__arm64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493429508,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493499876,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493559016,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493995440,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494788516,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495150484,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226900968,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 3226906868,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3226919728,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 3226941872,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 3227009360,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227058080,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 3227106032,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 3227460440,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:__se_sys_open_by_handle_at"
      ],
      "caller_func": []
    },
    {
      "addr": 3228209052,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 3228538120,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286837304,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286857064,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286863160,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286895596,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286987424,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287062404,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287132208,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287642856,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288623904,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289075260,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273042652,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273052204,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273056356,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273076634,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273129812,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273172914,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273217128,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273511868,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:__se_sys_open_by_handle_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274119958,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274397866,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581803357,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581818880,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823844,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845463,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909725,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581955969,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582003177,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364505,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051926,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583366886,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581741021,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756544,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761508,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783127,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847309,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581893537,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940745,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302201,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582989078,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303990,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581794669,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810192,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581815156,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836775,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901037,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947281,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994457,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354985,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040534,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350662,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_parent",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581863805,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879408,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884355,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906070,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970653,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:iterate_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017313,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:notify_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582064921,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582434601,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129670,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445846,
      "name": "fsnotify_parent",
      "external": false,
      "loc": "include/linux/fsnotify.h:34",
      "file": "security/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int fsnotify_parent(struct dentry * dentry, __u32 mask, const void * data, int data_type)
```
</details>
</li>
</ul>
