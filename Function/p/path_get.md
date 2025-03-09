# Function: <code>path_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033552,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:475",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/fs_struct.c:set_fs_root",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033552,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192752,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:485",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:SyS_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192752,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269968,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:485",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:SyS_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269968,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318928,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:485",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:SyS_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318928,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459152,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:485",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:SyS_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459152,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618480,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:469",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "ipc/shm.c:do_shmat",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618480,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581704864,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:469",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/path.c:aa_path_name",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704864,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822608,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822608,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895168,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895168,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133510,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:481",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/exec.c:kernel_read_file_from_path_initns",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_open_file",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124976,
      "name": "path_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582180013,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:481",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_open_file",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171456,
      "name": "path_get",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206054,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:531",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:get_path_from_fd",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196096,
      "name": "path_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582523825,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:542",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:get_path_from_fd",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513424,
      "name": "path_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583055473,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:543",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:get_path_from_fd",
        "security/landlock/fs.c:check_access_path_dual",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038128,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583621853,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:543",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:get_path_from_fd",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603328,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583840809,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:546",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:backing_file_open",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:get_path_from_fd",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820400,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584046841,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:547",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root"
      ],
      "caller_func": [
        "kernel/auditsc.c:audit_alloc_name",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_listmount",
        "fs/namespace.c:__x64_sys_listmount",
        "fs/namespace.c:__do_sys_statmount",
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/kernel_read_file.c:kernel_read_file_from_path_initns",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/backing-file.c:backing_file_open",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "security/landlock/syscalls.c:add_rule_path_beneath",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "drivers/block/loop.c:loop_get_status",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026352,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493374880,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493374880,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226961052,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226961052,
      "name": "path_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286922608,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286922608,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273092516,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273092516,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863904,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863904,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801504,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801504,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855216,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855216,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void path_get(const struct path * path)
```

```json
{
  "name": "path_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924704,
      "name": "path_get",
      "external": true,
      "loc": "fs/namei.c:467",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_getname",
        "fs/open.c:do_dentry_open",
        "fs/file_table.c:alloc_file_clone",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root",
        "fs/proc_namespace.c:mounts_open_common",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:proc_exe_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/fd.c:proc_fd_link",
        "fs/devpts/inode.c:devpts_acquire",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/dcookies.c:get_dcookie",
        "security/keys/big_key.c:big_key_preparse",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_unix_stream_connect",
        "security/apparmor/lsm.c:apparmor_sk_clone_security",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924704,
      "name": "path_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
