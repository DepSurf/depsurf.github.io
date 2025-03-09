# Function: <code>put_fs_context</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033072,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:491",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033072,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110848,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110848,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348528,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:434",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348528,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400160,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:434",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400160,
      "name": "put_fs_context",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582427424,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:434",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427424,
      "name": "put_fs_context",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750176,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:457",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750176,
      "name": "put_fs_context",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297600,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:457",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297600,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882432,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:457",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882432,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104112,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:478",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104112,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320368,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:508",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_single",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:fs_context_for_submount",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320368,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493652064,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__arm64_sys_fspick",
        "fs/fsopen.c:__arm64_sys_fspick",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493652064,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227185016,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227185016,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287242832,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287242832,
      "name": "put_fs_context",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273281870,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273281870,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079584,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079584,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017104,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017104,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070864,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070864,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void put_fs_context(struct fs_context * fc)
```

```json
{
  "name": "put_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142624,
      "name": "put_fs_context",
      "external": true,
      "loc": "fs/fs_context.c:489",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/fsopen.c:fscontext_release",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142624,
      "name": "put_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void put_fs_context(struct fs_context * fc)
```
</details>
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
