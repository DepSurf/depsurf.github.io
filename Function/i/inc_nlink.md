# Function: <code>inc_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101248,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:327",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_link",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_rename",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_file",
        "security/inode.c:securityfs_create_file",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101248,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266912,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:334",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266912,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344784,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:336",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344784,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400160,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:337",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:init_dir",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400160,
      "name": "inc_nlink",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541760,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:337",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:init_dir",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541760,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696048,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:339",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:init_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696048,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782400,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:339",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:init_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782400,
      "name": "inc_nlink",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:352",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:init_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912845,
      "name": "inc_nlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581901616,
      "name": "inc_nlink",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973664,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973664,
      "name": "inc_nlink",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206528,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:357",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206528,
      "name": "inc_nlink",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254000,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:358",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254000,
      "name": "inc_nlink",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279904,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:358",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279904,
      "name": "inc_nlink",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597904,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:362",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597904,
      "name": "inc_nlink",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129680,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:386",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129680,
      "name": "inc_nlink",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699120,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699120,
      "name": "inc_nlink",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916992,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916992,
      "name": "inc_nlink",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122768,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:385",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:__shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_rename_exchange",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122768,
      "name": "inc_nlink",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493485296,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493485296,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227043420,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227043420,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287039296,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287039296,
      "name": "inc_nlink",
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273157370,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273157370,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942400,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942400,
      "name": "inc_nlink",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879984,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879984,
      "name": "inc_nlink",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933712,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933712,
      "name": "inc_nlink",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void inc_nlink(struct inode * inode)
```

```json
{
  "name": "inc_nlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004832,
      "name": "inc_nlink",
      "external": true,
      "loc": "fs/inode.c:356",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkdir",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_rename2",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mkdir",
        "mm/shmem.c:shmem_get_inode",
        "fs/libfs.c:simple_rename",
        "fs/libfs.c:simple_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/configfs/mount.c:configfs_fill_super",
        "fs/ramfs/inode.c:ramfs_mkdir",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_mkdir",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/control.c:fuse_ctl_add_conn",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_automount",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/debugfs/inode.c:debugfs_create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/tracefs/inode.c:__create_dir",
        "fs/pstore/inode.c:pstore_fill_super",
        "fs/efivarfs/inode.c:efivarfs_get_inode",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/inode.c:securityfs_create_dentry",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004832,
      "name": "inc_nlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
