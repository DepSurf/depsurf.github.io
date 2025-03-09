# Function: <code>new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110320,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:901",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:mount_pseudo",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_file",
        "security/selinux/selinuxfs.c:sel_make_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110320,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275952,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:910",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/selinuxfs.c:sel_make_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275952,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354032,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:912",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/selinuxfs.c:sel_make_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354032,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409376,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:913",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409376,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550976,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:913",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550976,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581706880,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:918",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706880,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793728,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:926",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793728,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912336,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:939",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912336,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984928,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984928,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211808,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:951",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_perm_files",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211808,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259312,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/block_dev.c:bdev_alloc",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_perm_files",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259312,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285056,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:957",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/block_dev.c:bdev_alloc",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285056,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603536,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:961",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603536,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137344,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:1042",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137344,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708688,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:1040",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708688,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926144,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:1042",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926144,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133136,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:1027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:__shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_create_symlink",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:__debugfs_create_file",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133136,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493496136,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493496136,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227055312,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227055312,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287059088,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287059088,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273170914,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273170914,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953664,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953664,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891232,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891232,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944976,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944976,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct inode * new_inode(struct super_block * sb)
```

```json
{
  "name": "new_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015008,
      "name": "new_inode",
      "external": true,
      "loc": "fs/inode.c:950",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_inode",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:simple_fill_super",
        "fs/libfs.c:pseudo_fs_fill_super",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/configfs/inode.c:configfs_new_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/debugfs/inode.c:debugfs_get_inode",
        "fs/tracefs/inode.c:tracefs_get_inode",
        "fs/pstore/inode.c:pstore_get_inode",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_inode",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015008,
      "name": "new_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
