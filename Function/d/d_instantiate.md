# Function: <code>d_instantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090912,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1772",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_symlink",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:mount_pseudo",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_fill_super",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:SyS_io_setup",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/super.c:efivarfs_callback",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_file",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090912,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250416,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1808",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:__securityfs_setup_d_inode",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250416,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581328208,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1817",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:__securityfs_setup_d_inode",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328208,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581383600,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1847",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383600,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525056,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1859",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_dentry",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525056,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581683008,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1867",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/pipe.c:create_pipe_files",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/aio.c:aio_setup_ring",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683008,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581770256,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1875",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770256,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581887600,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/inode.c:configfs_create",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887600,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960160,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960160,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582192880,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1970",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192880,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582240384,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1977",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240384,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582266112,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:2004",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266112,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582585247,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:2005",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_make_root"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583952,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583115794,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:2030",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_make_root"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115232,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583686051,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:2030",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_make_root"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685152,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583903942,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:2030",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_make_root"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903328,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110507,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1874",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/dcache.c:d_make_root"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:__ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_mkdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110160,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493461344,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493461344,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227026752,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/nsfs.c:__ns_get_path",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227026752,
      "name": "d_instantiate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287018512,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287018512,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273141654,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273141654,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581928896,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928896,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581866480,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866480,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581920208,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920208,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void d_instantiate(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581990336,
      "name": "d_instantiate",
      "external": true,
      "loc": "fs/dcache.c:1949",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_make_root",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ext4/namei.c:ext4_link",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/ecryptfs/inode.c:ecryptfs_interpose",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990336,
      "name": "d_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
