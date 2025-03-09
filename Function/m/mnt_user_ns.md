# Function: <code>mnt_user_ns</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mnt_user_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579624887,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044144,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624342,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760656,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035988,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_write_event_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127754,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168616,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_getattr_nosec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175053,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:would_dump",
        "fs/exec.c:begin_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231346,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234021,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:setfl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243091,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282831,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_remove_privs",
        "fs/inode.c:atime_needs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306209,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_setattr_prepare",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:free_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345893,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411732,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/utimes.c:vfs_utimes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614466252,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_mkdir",
        "fs/init.c:init_symlink",
        "fs/init.c:init_link",
        "fs/init.c:init_mknod",
        "fs/init.c:path_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436046,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582486666,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_mnt_opts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582502969,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513106,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708718,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778491,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147973,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540235,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576699,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583868241,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584199369,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247018,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584259394,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:__file_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333288,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590520403,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_find_other"
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
  "name": "mnt_user_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579697955,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267136,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891820,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042704,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341268,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_write_event_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444394,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485912,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_getattr_nosec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492237,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:would_dump",
        "fs/exec.c:begin_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550218,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552587,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:setfl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560915,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600879,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_remove_privs",
        "fs/inode.c:atime_needs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625586,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_setattr_prepare",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:free_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582667909,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734116,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/utimes.c:vfs_utimes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615412292,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_mkdir",
        "fs/init.c:init_symlink",
        "fs/init.c:init_link",
        "fs/init.c:init_mknod",
        "fs/init.c:path_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758798,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582800874,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:show_mnt_opts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818025,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828431,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035294,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583105699,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488421,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583898219,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583934971,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584231421,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584584521,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632698,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645346,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:__file_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584721480,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591325010,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:78",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
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
  "name": "mnt_user_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579800165,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558300,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "kernel/bpf/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpf_obj_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289758,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582471801,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835281,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_write_event_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957421,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:dentry_create",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007188,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:vfs_getattr_nosec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583014289,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:would_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078595,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082610,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583090050,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134318,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:file_remove_privs",
        "fs/inode.c:atime_needs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161943,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_setattr_prepare",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:free_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206115,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:path_removexattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:path_getxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "fs/xattr.c:path_setxattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279624,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/utimes.c:vfs_utimes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617205547,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/init.c:init_mkdir",
        "fs/init.c:init_symlink",
        "fs/init.c:init_link",
        "fs/init.c:init_mknod",
        "fs/init.c:path_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308182,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583353562,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583375252,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_find_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387492,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509296,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587507,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584014934,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584474865,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514919,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584554771,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "fs/exportfs/expfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837613,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_creds_from_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231929,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585286939,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585302452,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:__file_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396736,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585998826,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_setxattr",
        "io_uring/io_uring.c:io_fsetxattr",
        "io_uring/io_uring.c:io_getxattr",
        "io_uring/io_uring.c:io_fgetxattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592992735,
      "name": "mnt_user_ns",
      "external": false,
      "loc": "include/linux/mount.h:76",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct user_namespace * mnt_user_ns(const struct vfsmount * mnt)
```

```json
{
  "name": "mnt_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731696,
      "name": "mnt_user_ns",
      "external": true,
      "loc": "fs/namespace.c:247",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/mincore.c:do_mincore",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:memcg_write_event_control",
        "fs/open.c:dentry_create",
        "fs/open.c:chown_common",
        "fs/open.c:chmod_common",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot",
        "fs/open.c:__ia32_sys_fchdir",
        "fs/open.c:__x64_sys_fchdir",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir",
        "fs/open.c:do_faccessat",
        "fs/open.c:do_sys_ftruncate",
        "fs/open.c:vfs_truncate",
        "fs/stat.c:vfs_getattr_nosec",
        "fs/exec.c:bprm_fill_uid",
        "fs/exec.c:would_dump",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_open",
        "fs/namei.c:pick_link",
        "fs/fcntl.c:setfl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/inode.c:__file_remove_privs",
        "fs/inode.c:__file_remove_privs",
        "fs/inode.c:atime_needs_update",
        "fs/utimes.c:vfs_utimes",
        "fs/init.c:init_mkdir",
        "fs/init.c:init_symlink",
        "fs/init.c:init_link",
        "fs/init.c:init_mknod",
        "fs/init.c:init_eaccess",
        "fs/init.c:init_chroot",
        "fs/init.c:init_chdir",
        "fs/notify/inotify/inotify_user.c:inotify_find_inode",
        "fs/notify/fanotify/fanotify_user.c:fanotify_find_path",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/coredump.c:do_coredump",
        "fs/ext4/ioctl.c:__ext4_ioctl",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/fat/file.c:fat_ioctl_set_attributes",
        "fs/exportfs/expfs.c:exportfs_decode_fh_raw",
        "fs/exportfs/expfs.c:reconnect_one",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond",
        "security/apparmor/file.c:__file_path_perm",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_find_other"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731696,
      "name": "mnt_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct user_namespace * mnt_user_ns(const struct vfsmount * mnt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct user_namespace * mnt_user_ns(const struct vfsmount * mnt)
```
</details>
</li>
</ul>
