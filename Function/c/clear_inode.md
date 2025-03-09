# Function: <code>clear_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101792,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:488",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101792,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267472,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:496",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267472,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345344,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:498",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345344,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400800,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:498",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "security/inode.c:securityfs_evict_inode",
        "security/apparmor/apparmorfs.c:aafs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400800,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542416,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:498",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "security/inode.c:securityfs_evict_inode",
        "security/apparmor/apparmorfs.c:aafs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542416,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697104,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:504",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "security/inode.c:securityfs_evict_inode",
        "security/apparmor/apparmorfs.c:aafs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697104,
      "name": "clear_inode",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783456,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:504",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_evict_inode",
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/debugfs/inode.c:debugfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "security/inode.c:securityfs_evict_inode",
        "security/apparmor/apparmorfs.c:aafs_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783456,
      "name": "clear_inode",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901456,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:517",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901456,
      "name": "clear_inode",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973872,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973872,
      "name": "clear_inode",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212000,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:522",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212000,
      "name": "clear_inode",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259504,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:523",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259504,
      "name": "clear_inode",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284912,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:523",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284912,
      "name": "clear_inode",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603392,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:527",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/bdev.c:bdev_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603392,
      "name": "clear_inode",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130016,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:604",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/bdev.c:bdev_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130016,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700208,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:603",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/bdev.c:bdev_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700208,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918080,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:603",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/bdev.c:bdev_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918080,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123888,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:604",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/fuse/inode.c:fuse_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/bdev.c:bdev_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123888,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493489056,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493489056,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227043244,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227043244,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287040256,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287040256,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273163484,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273163484,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942608,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942608,
      "name": "clear_inode",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880192,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880192,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933920,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933920,
      "name": "clear_inode",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void clear_inode(struct inode * inode)
```

```json
{
  "name": "clear_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005056,
      "name": "clear_inode",
      "external": true,
      "loc": "fs/inode.c:521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_evict_inode",
        "fs/inode.c:evict",
        "fs/nsfs.c:nsfs_evict",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_evict_inode",
        "fs/fat/inode.c:fat_evict_inode",
        "fs/ecryptfs/super.c:ecryptfs_evict_inode",
        "fs/pstore/inode.c:pstore_evict_inode",
        "fs/efivarfs/super.c:efivarfs_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005056,
      "name": "clear_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
