# Function: <code>unregister_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118688,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:101",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/hugetlbfs/inode.c:exit_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/selinuxfs.c:exit_sel_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118688,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284416,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:101",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/selinuxfs.c:exit_sel_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284416,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362832,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:101",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/selinuxfs.c:exit_sel_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362832,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418256,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:102",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418256,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559824,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:103",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:__dax_fs_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559824,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716912,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:103",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:exit_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716912,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581803632,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:103",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803632,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922496,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922496,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581994896,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994896,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227920,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227920,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582276320,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276320,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301856,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301856,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582620896,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620896,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156144,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156144,
      "name": "unregister_filesystem",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729888,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729888,
      "name": "unregister_filesystem",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946960,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946960,
      "name": "unregister_filesystem",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154400,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:108",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154400,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493510360,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493510360,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227065900,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227065900,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287075904,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287075904,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273182000,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273182000,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963632,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963632,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581901200,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901200,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954912,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954912,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int unregister_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "unregister_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024288,
      "name": "unregister_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:107",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/configfs/mount.c:configfs_exit",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:exit_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "fs/fuse/control.c:fuse_ctl_cleanup",
        "fs/pstore/inode.c:pstore_exit_fs",
        "fs/efivarfs/super.c:efivarfs_exit",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024288,
      "name": "unregister_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
