# Function: <code>kern_mount</code>

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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928112,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3764",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928112,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000720,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000720,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235760,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3850",
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
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235760,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284560,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3872",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284560,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310336,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:4278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310336,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629824,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:4356",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_cache_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629824,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166240,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:4449",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/shmem.c:shmem_init",
        "mm/zsmalloc.c:zs_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_cache_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166240,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740992,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:4558",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/shmem.c:shmem_init",
        "mm/secretmem.c:secretmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_cache_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740992,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957568,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:4750",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/shmem.c:shmem_init",
        "mm/secretmem.c:secretmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_cache_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957568,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167184,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:5205",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/secretmem.c:secretmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/nsfs.c:nsfs_init",
        "fs/anon_inodes.c:anon_inode_init",
        "fs/aio.c:aio_setup",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "block/bdev.c:bdev_cache_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167184,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493519728,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493519728,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227074220,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227074220,
      "name": "kern_mount",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287085488,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287085488,
      "name": "kern_mount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273187784,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273187784,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969456,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969456,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907024,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907024,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960736,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960736,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
```

```json
{
  "name": "kern_mount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031392,
      "name": "kern_mount",
      "external": true,
      "loc": "fs/namespace.c:3797",
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
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031392,
      "name": "kern_mount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct vfsmount * kern_mount(struct file_system_type * type)
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
