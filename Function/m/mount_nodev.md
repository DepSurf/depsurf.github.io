# Function: <code>mount_nodev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006464,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1118",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006464,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164752,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1138",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164752,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241728,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1184",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241728,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289072,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1183",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289072,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428736,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1183",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428736,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586960,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1238",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586960,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672864,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1223",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/hugetlbfs/inode.c:hugetlbfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672864,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790224,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1347",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:rootfs_mount",
        "kernel/bpf/inode.c:bpf_mount",
        "mm/shmem.c:shmem_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mount",
        "fs/fuse/inode.c:fuse_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790224,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862464,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862464,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088400,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088400,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134672,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1402",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134672,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159440,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1404",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159440,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476416,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1404",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476416,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998608,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1403",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998608,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560464,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1408",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560464,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583776608,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1425",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776608,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983280,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1685",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983280,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493332192,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493332192,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226929216,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226929216,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286876864,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286876864,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273065802,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273065802,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831200,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831200,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768864,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768864,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822512,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822512,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct dentry * mount_nodev(struct file_system_type * fs_type, int flags, void * data, int (*)(struct super_block *, void *, int) fill_super)
```

```json
{
  "name": "mount_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892768,
      "name": "mount_nodev",
      "external": true,
      "loc": "fs/super.c:1453",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/devpts/inode.c:devpts_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892768,
      "name": "mount_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
