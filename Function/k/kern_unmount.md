# Function: <code>kern_unmount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581127008,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3173",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:pid_ns_release_proc",
        "fs/hugetlbfs/inode.c:exit_hugetlbfs_fs",
        "ipc/mqueue.c:mq_put_mnt",
        "security/selinux/selinuxfs.c:exit_sel_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127008,
      "name": "kern_unmount",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292800,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3160",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "security/selinux/selinuxfs.c:exit_sel_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292800,
      "name": "kern_unmount",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581371632,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3304",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "security/selinux/selinuxfs.c:exit_sel_fs",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371632,
      "name": "kern_unmount",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581426832,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3240",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426832,
      "name": "kern_unmount",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568480,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3313",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568480,
      "name": "kern_unmount",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581724624,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3350",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724624,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581811136,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3322",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811136,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581931472,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3779",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931472,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582004096,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004096,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582239264,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3865",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239264,
      "name": "kern_unmount",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582288096,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3887",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288096,
      "name": "kern_unmount",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313648,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:4293",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313648,
      "name": "kern_unmount",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582633296,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:4371",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633296,
      "name": "kern_unmount",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583169680,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:4464",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169680,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744400,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:4573",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744400,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960912,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:4765",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_unload_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960912,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174112,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:5220",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:do_sysctl_args",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174112,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493524952,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493524952,
      "name": "kern_unmount",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227077264,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227077264,
      "name": "kern_unmount",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287091072,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287091072,
      "name": "kern_unmount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273191908,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273191908,
      "name": "kern_unmount",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581972832,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972832,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581910400,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910400,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964112,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964112,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void kern_unmount(struct vfsmount * mnt)
```

```json
{
  "name": "kern_unmount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582034528,
      "name": "kern_unmount",
      "external": true,
      "loc": "fs/namespace.c:3812",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_exit",
        "mm/zsmalloc.c:zs_init",
        "fs/proc/root.c:pid_ns_release_proc",
        "ipc/mqueue.c:mq_put_mnt",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/dma-buf/dma-buf.c:dma_buf_deinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034528,
      "name": "kern_unmount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
