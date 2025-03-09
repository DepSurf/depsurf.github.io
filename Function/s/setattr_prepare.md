# Function: <code>setattr_prepare</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355104,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:57",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355104,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410448,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:58",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410448,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552048,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:59",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552048,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581708144,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708144,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794656,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794656,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913472,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913472,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985760,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985760,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219488,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219488,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266944,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266944,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582292288,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:96",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292288,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
int setattr_prepare(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611088,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:96",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611088,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int setattr_prepare(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145792,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:102",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145792,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int setattr_prepare(struct user_namespace * mnt_userns, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583716944,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:164",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716944,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
int setattr_prepare(struct mnt_idmap * idmap, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934416,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:165",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934416,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
int setattr_prepare(struct mnt_idmap * idmap, struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140656,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:165",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140656,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493498576,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493498576,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227056452,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227056452,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287060416,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287060416,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273171728,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273171728,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954496,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954496,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892064,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892064,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945808,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945808,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```

```json
{
  "name": "setattr_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015840,
      "name": "setattr_prepare",
      "external": true,
      "loc": "fs/attr.c:61",
      "file": "fs/attr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_setattr",
        "fs/libfs.c:simple_setattr",
        "fs/proc/base.c:proc_setattr",
        "fs/proc/generic.c:proc_notify_change",
        "fs/proc/proc_sysctl.c:proc_sys_setattr",
        "fs/kernfs/inode.c:kernfs_iop_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/fat/file.c:fat_setattr",
        "fs/ecryptfs/inode.c:ecryptfs_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015840,
      "name": "setattr_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int setattr_prepare(struct dentry * dentry, struct iattr * attr)
```
</details>
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
<code>dentry, attr</code> ➡️ <code>mnt_userns, dentry, attr</code>
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
