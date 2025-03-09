# Function: <code>fsnotify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fsnotify(struct inode * to_tell, __u32 mask, void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266576,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:190",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/open.c:do_sys_open",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:vfs_write",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:vfs_removexattr",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266576,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1181
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
int fsnotify(struct inode * to_tell, __u32 mask, void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432304,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:190",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432304,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1159
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513424,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:190",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513424,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1159
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566160,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:252",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566160,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1223
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710288,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:275",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710288,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581877104,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877104,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1487
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const unsigned char * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962224,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:327",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962224,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 947
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094896,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:314",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094896,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172256,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172256,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409664,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:311",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
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
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/libfs.c:simple_recursive_removal",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409664,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582463072,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:462",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_sys_openat2",
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
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/libfs.c:simple_recursive_removal",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463072,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489920,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:462",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_sys_openat2",
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
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/libfs.c:simple_recursive_removal",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489920,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804272,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:462",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_sys_openat2",
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
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804272,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1034
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357408,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:478",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_sys_openat2",
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
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:vfs_read",
        "fs/read_write.c:__kernel_read",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_fallocate",
        "io_uring/io_uring.c:__io_complete_rw_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357408,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1685
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940768,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:481",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_sys_openat2",
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
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "io_uring/sync.c:io_fallocate",
        "io_uring/openclose.c:io_openat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940768,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1698
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163984,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:481",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
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
        "fs/file_table.c:__fput",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163984,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1794
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
int fsnotify(__u32 mask, const void * data, int data_type, struct inode * dir, const struct qstr * file_name, struct inode * inode, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378176,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:481",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:latency_fsnotify_workfn",
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_fallocate",
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
        "fs/read_write.c:rw_verify_area",
        "fs/file_table.c:__fput",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_removexattr_locked",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/libfs.c:simple_recursive_removal",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_tee",
        "fs/splice.c:__do_sys_vmsplice",
        "fs/splice.c:vmsplice_to_pipe",
        "fs/splice.c:do_splice",
        "fs/splice.c:do_splice",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/posix_acl.c:vfs_remove_acl",
        "fs/posix_acl.c:vfs_set_acl",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_rename",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378176,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1794
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493727048,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__arm64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493727048,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227252880,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227252880,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287334720,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287334720,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1308
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273337164,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273337164,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140992,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140992,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078432,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078432,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131472,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131472,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int fsnotify(struct inode * to_tell, __u32 mask, const void * data, int data_is, const struct qstr * file_name, u32 cookie)
```

```json
{
  "name": "fsnotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204784,
      "name": "fsnotify",
      "external": true,
      "loc": "fs/notify/fsnotify.c:318",
      "file": "fs/notify/fsnotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:do_sys_open",
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_sendfile",
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:__kernel_write",
        "fs/file_table.c:__fput",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/readdir.c:iterate_dir",
        "fs/dcache.c:dentry_unlink_inode",
        "fs/attr.c:notify_change",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/xattr.c:__vfs_setxattr_noperm",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:__fsnotify_parent",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/fhandle.c:do_handle_open",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/devpts/inode.c:devpts_pty_kill",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/security.c:security_file_open",
        "security/security.c:security_file_open",
        "security/security.c:security_file_permission",
        "security/security.c:security_file_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204784,
      "name": "fsnotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * data</code> ➡️ <code>const void * data</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char * file_name</code> ➡️ <code>const struct qstr * file_name</code>
</li>
</ul>
</details>
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
<code>int data_type</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode * dir</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * to_tell</code>
</li>
<li>
<b>Param removed. </b>
<code>int data_is</code>
</li>
<li>
<b>Param reordered. </b>
<code>to_tell, mask, data, data_is, file_name, cookie</code> ➡️ <code>mask, data, data_type, dir, file_name, inode, cookie</code>
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
