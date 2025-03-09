# Function: <code>unlock_mount_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581121484,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:115",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:vfs_kern_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:sb_prepare_remount_readonly",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:SyS_pivot_root"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581304821,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:115",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_kern_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383859,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:123",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_kern_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581439125,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:124",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581013,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:125",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581736952,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:125",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581823640,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:125",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581947642,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582020218,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255832,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:133",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305128,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:132",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:do_reconfigure_mnt",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582332752,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:105",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582653344,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:105",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unlock_mount_hash()
```

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190792,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:106",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157648,
      "name": "unlock_mount_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void unlock_mount_hash()
```

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766086,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:123",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731600,
      "name": "unlock_mount_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void unlock_mount_hash()
```

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583983238,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:107",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948640,
      "name": "unlock_mount_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void unlock_mount_hash()
```

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584195778,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/namespace.c:111",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:do_set_group",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:__legitimize_mnt",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156080,
      "name": "unlock_mount_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493542120,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void unlock_mount_hash()
```

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227089956,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_move_mount",
        "fs/namespace.c:set_mount_attributes",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227067476,
      "name": "unlock_mount_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287112556,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:may_umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273207066,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581988954,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581926522,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581980234,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
  "name": "unlock_mount_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582050728,
      "name": "unlock_mount_hash",
      "external": false,
      "loc": "fs/mount.h:127",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:open_detached_copy",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:sb_prepare_remount_readonly"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void unlock_mount_hash()
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void unlock_mount_hash()
```
</details>
</li>
</ul>
