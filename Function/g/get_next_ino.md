# Function: <code>get_next_ino</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101168,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:842",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_file",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101168,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266832,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:851",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266832,
      "name": "get_next_ino",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344704,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:853",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344704,
      "name": "get_next_ino",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400224,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:854",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400224,
      "name": "get_next_ino",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541824,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:854",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541824,
      "name": "get_next_ino",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696112,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:859",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696112,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782464,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:867",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782464,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901312,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:880",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901312,
      "name": "get_next_ino",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973728,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973728,
      "name": "get_next_ino",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206592,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:892",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:get_pipe_inode",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206592,
      "name": "get_next_ino",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254064,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "fs/pipe.c:get_pipe_inode",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254064,
      "name": "get_next_ino",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279968,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:898",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279968,
      "name": "get_next_ino",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598016,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:902",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598016,
      "name": "get_next_ino",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129824,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:983",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129824,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699296,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:982",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699296,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917168,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:984",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917168,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122944,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:969",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/event_inode.c:eventfs_iterate",
        "fs/tracefs/event_inode.c:eventfs_root_lookup",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122944,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493485160,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493485160,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227043124,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227043124,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287039392,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287039392,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273157450,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273157450,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942464,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942464,
      "name": "get_next_ino",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880048,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880048,
      "name": "get_next_ino",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933776,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933776,
      "name": "get_next_ino",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int get_next_ino()
```

```json
{
  "name": "get_next_ino",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004896,
      "name": "get_next_ino",
      "external": true,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/pipe.c:create_pipe_files",
        "fs/libfs.c:alloc_anon_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004896,
      "name": "get_next_ino",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
