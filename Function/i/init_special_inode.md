# Function: <code>init_special_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104480,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1909",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104480,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269664,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1926",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269664,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347264,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1976",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347264,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402720,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1966",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402720,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544352,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1979",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544352,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1971",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707741,
      "name": "init_special_inode.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581698752,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:1978",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794253,
      "name": "init_special_inode.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581785104,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2016",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912864,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581901696,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985437,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581975760,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2111",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219163,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582207824,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2112",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_whiteout_for_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_mk_null_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339791,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582255296,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2121",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282507,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582280944,
      "name": "init_special_inode",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2126",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229860,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582598992,
      "name": "init_special_inode",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2207",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594009617,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583130448,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700720,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2260",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700720,
      "name": "init_special_inode",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920800,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2304",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920800,
      "name": "init_special_inode",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126496,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2307",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_init_inode",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126496,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493481536,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493481536,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227046496,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227046496,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287042816,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287042816,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273159242,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273159242,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954173,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581944496,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891741,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581882064,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945485,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071581935808,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void init_special_inode(struct inode * inode, umode_t mode, dev_t rdev)
```

```json
{
  "name": "init_special_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_special_inode",
      "external": true,
      "loc": "fs/inode.c:2027",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_inode",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mknod",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/squashfs/inode.c:squashfs_read_inode",
        "fs/ramfs/inode.c:ramfs_get_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_get_inode",
        "fs/ecryptfs/inode.c:ecryptfs_inode_set",
        "fs/fuse/inode.c:fuse_iget",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/apparmor/apparmorfs.c:aa_create_aafs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015517,
      "name": "init_special_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582007248,
      "name": "init_special_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
