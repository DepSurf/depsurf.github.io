# Function: <code>getname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581057072,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:204",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:user_path_mountpoint_at",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "fs/open.c:do_sys_open",
        "fs/exec.c:SyS_uselib",
        "fs/exec.c:SyS_execve",
        "fs/exec.c:compat_SyS_execve",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057072,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581228538,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:206",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:compat_SyS_execve",
        "fs/exec.c:SyS_execve",
        "fs/exec.c:SyS_uselib",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217968,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581306198,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:206",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:compat_SyS_execve",
        "fs/exec.c:SyS_execve",
        "fs/exec.c:SyS_uselib",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295664,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581355664,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:206",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:compat_SyS_execve",
        "fs/exec.c:SyS_execve",
        "fs/exec.c:SyS_uselib",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345216,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581497120,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_link",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_unlink",
        "fs/namei.c:SyS_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:SyS_mkdir",
        "fs/namei.c:SyS_mknod",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:compat_SyS_execve",
        "fs/exec.c:SyS_execve",
        "fs/exec.c:SyS_uselib",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486608,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648775,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:209",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646688,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735047,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:209",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732960,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581851143,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849664,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581923623,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922160,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582153745,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat"
      ],
      "caller_func": [
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/io_uring.c:__io_openat_prep",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151504,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582207093,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:do_mkdirat"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:__io_openat_prep",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197600,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232069,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:do_mkdirat"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:__io_openat_prep",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222256,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582550565,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:215",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__x64_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_req_prep",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540960,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583079028,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:216",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:__io_openat_prep",
        "io_uring/io_uring.c:io_linkat_prep",
        "io_uring/io_uring.c:io_linkat_prep",
        "io_uring/io_uring.c:io_symlinkat_prep",
        "io_uring/io_uring.c:io_symlinkat_prep",
        "io_uring/io_uring.c:io_mkdirat_prep",
        "io_uring/io_uring.c:io_unlinkat_prep",
        "io_uring/io_uring.c:io_renameat_prep",
        "io_uring/io_uring.c:io_renameat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068368,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583646052,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:216",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__do_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_prep",
        "io_uring/fs.c:io_unlinkat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:__io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634544,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583863252,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:217",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_prep",
        "io_uring/fs.c:io_unlinkat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:__io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853312,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584070292,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:217",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__ia32_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__x64_sys_rename",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__x64_sys_renameat",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__ia32_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__x64_sys_renameat2",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:__ia32_sys_rmdir",
        "fs/namei.c:__x64_sys_rmdir",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/namei.c:__ia32_sys_mknod",
        "fs/namei.c:__x64_sys_mknod",
        "fs/namei.c:__ia32_sys_mknodat",
        "fs/namei.c:__x64_sys_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:user_path_locked_at"
      ],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_prep",
        "io_uring/fs.c:io_unlinkat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:__io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060496,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493404376,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__arm64_sys_unlink",
        "fs/namei.c:__arm64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__arm64_compat_sys_execve",
        "fs/exec.c:__arm64_sys_execve",
        "fs/exec.c:__arm64_sys_uselib",
        "fs/filesystems.c:__arm64_sys_sysfs",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493402896,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226990420,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__se_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__se_sys_execve",
        "fs/exec.c:__se_sys_uselib",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226988992,
      "name": "getname",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286962144,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__se_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__se_compat_sys_execve",
        "fs/exec.c:__se_sys_execve",
        "fs/exec.c:__se_sys_uselib",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286960192,
      "name": "getname",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273116050,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__se_sys_unlink",
        "fs/namei.c:__se_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__se_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__se_sys_execve",
        "fs/exec.c:__se_sys_uselib",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273114902,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581892359,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890896,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829959,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828496,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883671,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882208,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct filename * getname(const char * filename)
```

```json
{
  "name": "getname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581953175,
      "name": "getname",
      "external": true,
      "loc": "fs/namei.c:207",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:__ia32_sys_unlink",
        "fs/namei.c:__x64_sys_unlink",
        "fs/namei.c:__ia32_sys_unlinkat",
        "fs/namei.c:__x64_sys_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_initrd.c:initrd_load",
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:clean_path",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/exec.c:__x32_compat_sys_execve",
        "fs/exec.c:__ia32_compat_sys_execve",
        "fs/exec.c:__ia32_sys_execve",
        "fs/exec.c:__x64_sys_execve",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/filesystems.c:fs_index",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951712,
      "name": "getname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
