# Function: <code>fuse_simple_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061408,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:552",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_getxattr",
        "fs/fuse/dir.c:fuse_getxattr",
        "fs/fuse/dir.c:fuse_follow_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_listxattr",
        "fs/fuse/dir.c:fuse_listxattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/inode.c:fuse_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061408,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275536,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:527",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_removexattr",
        "fs/fuse/dir.c:fuse_listxattr",
        "fs/fuse/dir.c:fuse_listxattr",
        "fs/fuse/dir.c:fuse_getxattr",
        "fs/fuse/dir.c:fuse_getxattr",
        "fs/fuse/dir.c:fuse_setxattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275536,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364912,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:531",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364912,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449264,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:531",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449264,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600048,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:531",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600048,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792848,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:544",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792848,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582897216,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:600",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897216,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076224,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:624",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076224,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181712,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181712,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583505776,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583505776,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614432,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:487",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614432,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583637216,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:487",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637216,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
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
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996368,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:487",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996368,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580080,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:483",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580080,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257360,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:483",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257360,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487024,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:485",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487024,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
ssize_t fuse_simple_request(struct fuse_mount * fm, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585722384,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:485",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_do_statx",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rmdir",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_sync_fs",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_priv_ioctl",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "fs/fuse/dax.c:fuse_send_removemapping",
        "fs/fuse/dax.c:fuse_setup_one_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722384,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494897544,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494897544,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228310784,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_file_llseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_do_open",
        "fs/fuse/inode.c:fuse_sb_destroy",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228310784,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1476
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288762336,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288762336,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274211482,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_send_open",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274211482,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150448,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150448,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583087600,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583087600,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134480,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134480,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
ssize_t fuse_simple_request(struct fuse_conn * fc, struct fuse_args * args)
```

```json
{
  "name": "fuse_simple_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583228064,
      "name": "fuse_simple_request",
      "external": true,
      "loc": "fs/fuse/dev.c:476",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_flush_times",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/dir.c:fuse_access",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_lseek",
        "fs/fuse/file.c:fuse_bmap",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/inode.c:fuse_statfs",
        "fs/fuse/inode.c:fuse_send_destroy",
        "fs/fuse/xattr.c:fuse_removexattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_listxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_getxattr",
        "fs/fuse/xattr.c:fuse_setxattr",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_force_forget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228064,
      "name": "fuse_simple_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount * fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn * fc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
