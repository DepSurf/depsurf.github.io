# Function: <code>mntput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581126720,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1137",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:drop_mountpoint",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:mount_subtree"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_mount",
        "fs/namei.c:done_path_create",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/libfs.c:simple_pin_fs",
        "fs/libfs.c:simple_release_fs",
        "fs/nsfs.c:ns_get_path",
        "fs/nsfs.c:ns_get_path",
        "fs/nsfs.c:ns_get_path",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126720,
      "name": "mntput",
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581305125,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1137",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:ns_get_path",
        "fs/nsfs.c:ns_get_path",
        "fs/nsfs.c:ns_get_path",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292512,
      "name": "mntput",
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581384149,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1182",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371344,
      "name": "mntput",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439429,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1183",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426544,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581581301,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1248",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_link",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568192,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581738306,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1274",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724336,
      "name": "mntput",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581824994,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1186",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:drop_mountpoint"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811072,
      "name": "mntput",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581949030,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930016,
      "name": "mntput",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582021606,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002624,
      "name": "mntput",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582238706,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1212",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:choose_mountpoint",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238576,
      "name": "mntput",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582287538,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1215",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "kernel/usermode_driver.c:blob_to_mnt",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_tmpfile",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:choose_mountpoint",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287408,
      "name": "mntput",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313090,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1225",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312960,
      "name": "mntput",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582632674,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1234",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632544,
      "name": "mntput",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583168992,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1275",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583168848,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583743760,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1380",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743600,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583960272,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1343",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:kern_unmount",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "ipc/namespace.c:free_ipc",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960112,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584173472,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1356",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:kern_unmount_array",
        "fs/namespace.c:kern_unmount",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt",
        "fs/namespace.c:lookup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:__kern_path_locked",
        "fs/namei.c:__kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:step_into",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:handle_to_path",
        "fs/devpts/inode.c:devpts_mntget",
        "ipc/namespace.c:free_ipc",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173312,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493542552,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/acct.c:__arm64_sys_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493523352,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227093516,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227075796,
      "name": "mntput",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287113060,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287088896,
      "name": "mntput",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273197972,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273190568,
      "name": "mntput",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581990342,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971360,
      "name": "mntput",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581927910,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908928,
      "name": "mntput",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581981622,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962640,
      "name": "mntput",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void mntput(struct vfsmount * mnt)
```

```json
{
  "name": "mntput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582052086,
      "name": "mntput",
      "external": true,
      "loc": "fs/namespace.c:1196",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:finish_automount",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:cleanup_mnt"
      ],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "fs/file_table.c:__fput",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:done_path_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:path_openat",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:walk_component",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_link",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/namei.c:terminate_walk",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/devpts/inode.c:devpts_mntget",
        "drivers/tty/pty.c:ptm_open_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033072,
      "name": "mntput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
