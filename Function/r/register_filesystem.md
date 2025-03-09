# Function: <code>register_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119248,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:69",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cpuset.c:cpuset_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119248,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284976,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:69",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cpuset.c:cpuset_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284976,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581363392,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:69",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cpuset.c:cpuset_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363392,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418128,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:70",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "mm/shmem.c:shmem_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418128,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559696,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:71",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "mm/shmem.c:shmem_init",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559696,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715872,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:71",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:init_pstore_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:dax_fs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715872,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802592,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:71",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/dax/super.c:dax_fs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802592,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921456,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921456,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993840,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993840,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227696,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227696,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276096,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276096,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301632,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301632,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620672,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "block/bdev.c:bdev_cache_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620672,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155904,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "block/bdev.c:bdev_cache_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155904,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729632,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "block/bdev.c:bdev_cache_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729632,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946704,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "block/bdev.c:bdev_cache_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946704,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154144,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "block/bdev.c:bdev_cache_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154144,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493510000,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493510000,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227065716,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227065716,
      "name": "register_filesystem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287073424,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287073424,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273181366,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273181366,
      "name": "register_filesystem",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962576,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962576,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900144,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900144,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953888,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953888,
      "name": "register_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int register_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "register_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024128,
      "name": "register_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:72",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/bpf/inode.c:bpf_init",
        "mm/shmem.c:shmem_init",
        "fs/pipe.c:init_pipe_fs",
        "fs/block_dev.c:bdev_cache_init",
        "fs/proc/root.c:proc_root_init",
        "fs/sysfs/mount.c:sysfs_init",
        "fs/configfs/mount.c:configfs_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/ramfs/inode.c:init_ramfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/namei_vfat.c:init_vfat_fs",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/control.c:fuse_ctl_init",
        "fs/debugfs/inode.c:debugfs_init",
        "fs/tracefs/inode.c:tracefs_init",
        "fs/pstore/inode.c:pstore_init_fs",
        "fs/efivarfs/super.c:efivarfs_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/inode.c:securityfs_init",
        "security/selinux/selinuxfs.c:init_sel_fs",
        "security/smack/smackfs.c:init_smk_fs",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "net/socket.c:sock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024128,
      "name": "register_filesystem",
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
