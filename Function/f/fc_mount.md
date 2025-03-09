# Function: <code>fc_mount</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581927792,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927792,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000400,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000400,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582235408,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:984",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235408,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284208,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:984",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284208,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582309984,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:991",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309984,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582629472,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:1000",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629472,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165776,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:1041",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165776,
      "name": "fc_mount",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583740464,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:1147",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740464,
      "name": "fc_mount",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583957040,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:1110",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957040,
      "name": "fc_mount",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166656,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:1123",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "ipc/mqueue.c:mq_init_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166656,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493519232,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493519232,
      "name": "fc_mount",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227073872,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227073872,
      "name": "fc_mount",
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287084944,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287084944,
      "name": "fc_mount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273187372,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273187372,
      "name": "fc_mount",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581969136,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969136,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581906704,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906704,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960416,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960416,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
```

```json
{
  "name": "fc_mount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582031136,
      "name": "fc_mount",
      "external": true,
      "loc": "fs/namespace.c:968",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:mount_one_hugetlbfs",
        "ipc/mqueue.c:mq_create_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031136,
      "name": "fc_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct vfsmount * fc_mount(struct fs_context * fc)
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
