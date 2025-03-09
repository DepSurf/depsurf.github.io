# Function: <code>inode_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036288,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:458",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:vfs_truncate",
        "fs/open.c:SyS_access",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_fchdir",
        "fs/open.c:SyS_chroot",
        "fs/exec.c:setup_new_exec",
        "fs/namei.c:may_linkat",
        "fs/namei.c:may_open",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:may_delete",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_link",
        "fs/namei.c:path_init",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/xattr.c:xattr_permission",
        "fs/utimes.c:utimes_common",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036288,
      "name": "inode_permission",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195680,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:468",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_fchdir",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:setup_new_exec",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_open",
        "fs/namei.c:may_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:may_linkat",
        "fs/xattr.c:xattr_permission",
        "fs/utimes.c:utimes_common",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195680,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272960,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:468",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_fchdir",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:may_open",
        "fs/namei.c:may_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:path_init",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:may_linkat",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272960,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322496,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:468",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_fchdir",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:may_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:may_linkat",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322496,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462800,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:468",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:SyS_chroot",
        "fs/open.c:SyS_fchdir",
        "fs/open.c:SyS_chdir",
        "fs/open.c:SyS_access",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:may_open",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:may_linkat",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462800,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628784,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:427",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628784,
      "name": "inode_permission",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714960,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:427",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:path_openat",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714960,
      "name": "inode_permission",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832464,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832464,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904928,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904928,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582148742,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:439",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_o_create",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135936,
      "name": "inode_permission.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071582136224,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582194939,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:439",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_o_create",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_do_get",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_o_create",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182432,
      "name": "inode_permission.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071582182720,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int inode_permission(struct user_namespace * mnt_userns, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206336,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:488",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common",
        "fs/namei.c:may_linkat",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:path_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206336,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int inode_permission(struct user_namespace * mnt_userns, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582524096,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:499",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_common",
        "fs/namei.c:may_linkat",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:path_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524096,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int inode_permission(struct user_namespace * mnt_userns, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583045472,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:500",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_common",
        "fs/namei.c:may_linkat",
        "fs/attr.c:may_setattr",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:path_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045472,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int inode_permission(struct user_namespace * mnt_userns, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583610976,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:500",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_common",
        "fs/namei.c:may_linkat",
        "fs/attr.c:may_setattr",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610976,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int inode_permission(struct mnt_idmap * idmap, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583824128,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:503",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_common",
        "fs/namei.c:may_linkat",
        "fs/attr.c:may_setattr",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824128,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int inode_permission(struct mnt_idmap * idmap, struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584030192,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:504",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/trace/bpf_trace.c:bpf_get_file_xattr",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_mknod",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_common",
        "fs/namei.c:may_linkat",
        "fs/attr.c:may_setattr",
        "fs/xattr.c:xattr_permission",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030192,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493385472,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__arm64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493385472,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226967012,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__se_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:may_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:__se_sys_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226967012,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286927536,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__se_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286927536,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273101306,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__se_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/namei.c:lookup_one_len_common",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:__se_sys_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273101306,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873664,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873664,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811264,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811264,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864976,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864976,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int inode_permission(struct inode * inode, int mask)
```

```json
{
  "name": "inode_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927920,
      "name": "inode_permission",
      "external": true,
      "loc": "fs/namei.c:425",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_permission",
        "kernel/bpf/inode.c:bpf_prog_get_type_path",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:ksys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:ksys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/exec.c:would_dump",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:do_linkat",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_mkdir",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:vfs_mkobj",
        "fs/namei.c:may_delete",
        "fs/attr.c:notify_change",
        "fs/xattr.c:xattr_permission",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_permission",
        "ipc/mqueue.c:do_mq_open",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927920,
      "name": "inode_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask</code> ➡️ <code>mnt_userns, inode, mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
