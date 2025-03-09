# Function: <code>kern_mount_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124432,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3158",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124432,
      "name": "kern_mount_data",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290208,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3145",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290208,
      "name": "kern_mount_data",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369408,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3289",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369408,
      "name": "kern_mount_data",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425088,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3225",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425088,
      "name": "kern_mount_data",
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
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566352,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3298",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566352,
      "name": "kern_mount_data",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722192,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3335",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722192,
      "name": "kern_mount_data",
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
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```

```json
{
  "name": "kern_mount_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809232,
      "name": "kern_mount_data",
      "external": true,
      "loc": "fs/namespace.c:3307",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809232,
      "name": "kern_mount_data",
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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct vfsmount * kern_mount_data(struct file_system_type * type, void * data)
```
</details>
</li>
</ul>
