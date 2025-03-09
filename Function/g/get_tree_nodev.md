# Function: <code>get_tree_nodev</code>

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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791728,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1198",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:pseudo_fs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791728,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866272,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866272,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090336,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090336,
      "name": "get_tree_nodev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136176,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1164",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136176,
      "name": "get_tree_nodev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161136,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1166",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161136,
      "name": "get_tree_nodev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477920,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1166",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477920,
      "name": "get_tree_nodev",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998784,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1165",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998784,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562928,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1166",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562928,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779232,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1177",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779232,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981728,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1283",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/proc/root.c:proc_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree",
        "fs/fuse/inode.c:fuse_get_tree",
        "ipc/mqueue.c:mqueue_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981728,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493337832,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493337832,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226931988,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226931988,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286881392,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286881392,
      "name": "get_tree_nodev",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273068574,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273068574,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835008,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835008,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772672,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772672,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826320,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826320,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
```

```json
{
  "name": "get_tree_nodev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895504,
      "name": "get_tree_nodev",
      "external": true,
      "loc": "fs/super.c:1217",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_get_tree",
        "mm/shmem.c:shmem_get_tree",
        "fs/libfs.c:pseudo_fs_get_tree",
        "fs/ramfs/inode.c:ramfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895504,
      "name": "get_tree_nodev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int get_tree_nodev(struct fs_context * fc, int (*)(struct super_block *, struct fs_context *) fill_super)
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
