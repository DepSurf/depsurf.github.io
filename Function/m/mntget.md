# Function: <code>mntget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581120016,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1149",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_get",
        "fs/namei.c:follow_managed",
        "fs/namei.c:pick_link",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_openat",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:SyS_io_setup",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:SyS_mq_open",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120016,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303528,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1149",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:SyS_mq_open",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285760,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581382528,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1194",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:SyS_mq_open",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364304,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581437762,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1195",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419680,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581579650,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1260",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561296,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735510,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1286",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/pipe.c:create_pipe_files",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/aio.c:aio_setup_ring",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc_file",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717520,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581822214,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1198",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804320,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938291,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923424,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582010931,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995824,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582247434,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1224",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229824,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582296682,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1227",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278064,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582323391,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1237",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__do_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303600,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582643843,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1246",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__do_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622528,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583181682,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1287",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157904,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583756801,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1392",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732048,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583973732,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1355",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948944,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584185981,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1368",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:step_into",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:handle_to_path",
        "fs/fhandle.c:handle_to_path",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156384,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493532848,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__arm64_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493517776,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227091428,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__se_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/nsfs.c:__ns_get_path",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227068204,
      "name": "mntget",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287101036,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__se_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287083648,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273205528,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__se_sys_open_tree"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:__se_sys_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273183282,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581979667,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964560,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581917235,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902128,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581970947,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955840,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct vfsmount * mntget(struct vfsmount * mnt)
```

```json
{
  "name": "mntget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582042195,
      "name": "mntget",
      "external": true,
      "loc": "fs/namespace.c:1208",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:open_detached_copy"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_automount",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/namei.c:pick_link",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/libfs.c:simple_pin_fs",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "ipc/mqueue.c:do_mq_open",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026048,
      "name": "mntget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
