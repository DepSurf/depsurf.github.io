# Function: <code>putname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581056480,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:244",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/auditsc.c:__audit_free",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "fs/open.c:filp_open",
        "fs/open.c:do_sys_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:filename_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056480,
      "name": "putname",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581217376,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:246",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217376,
      "name": "putname",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581295072,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:246",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295072,
      "name": "putname",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581344640,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:246",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344640,
      "name": "putname",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581486016,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:247",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:SyS_uselib",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_symlink",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:SyS_sysfs",
        "fs/quota/quota.c:SyS_quotactl",
        "ipc/mqueue.c:SyS_mq_unlink",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486016,
      "name": "putname",
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646128,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:250",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
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
      "addr": 18446744071581646128,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732400,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:250",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
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
      "addr": 18446744071581732400,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581849088,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849088,
      "name": "putname",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921584,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921584,
      "name": "putname",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582150880,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/io_uring.c:io_cleanup_req",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150880,
      "name": "putname",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582196976,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:do_execveat_common",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/io_uring.c:__io_clean_op",
        "fs/io_uring.c:__io_clean_op",
        "fs/io_uring.c:__io_clean_op",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196976,
      "name": "putname",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582221632,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221632,
      "name": "putname",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582540336,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:256",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_clean_op",
        "fs/io_uring.c:io_req_prep",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540336,
      "name": "putname",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583067696,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:257",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:audit_reset_context",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_clean_op",
        "io_uring/io_uring.c:io_clean_op",
        "io_uring/io_uring.c:io_clean_op",
        "io_uring/io_uring.c:io_clean_op",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_openat2",
        "io_uring/io_uring.c:io_linkat_prep",
        "io_uring/io_uring.c:io_symlinkat_prep",
        "io_uring/io_uring.c:io_setxattr",
        "io_uring/io_uring.c:io_fsetxattr",
        "io_uring/io_uring.c:io_getxattr",
        "io_uring/io_uring.c:io_fgetxattr",
        "io_uring/io_uring.c:io_renameat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067696,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633824,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:257",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:audit_reset_context",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__do_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr",
        "io_uring/xattr.c:io_getxattr",
        "io_uring/xattr.c:io_fgetxattr",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_cleanup",
        "io_uring/fs.c:io_unlinkat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:io_open_cleanup",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/statx.c:io_statx_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633824,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583822096,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:259",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:audit_reset_context",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:vfs_fstatat",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:kern_path_locked",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr",
        "io_uring/xattr.c:io_getxattr",
        "io_uring/xattr.c:io_fgetxattr",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_cleanup",
        "io_uring/fs.c:io_unlinkat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:io_open_cleanup",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/statx.c:io_statx_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822096,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584029056,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:259",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:audit_reset_context",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/open.c:do_sys_openat2",
        "fs/open.c:filp_open",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat",
        "fs/exec.c:kernel_execve",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_linkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:do_mkdirat",
        "fs/namei.c:do_mknodat",
        "fs/namei.c:user_path_create",
        "fs/namei.c:kern_path_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:user_path_at_empty",
        "fs/namei.c:vfs_path_lookup",
        "fs/namei.c:kern_path",
        "fs/namei.c:user_path_locked_at",
        "fs/namei.c:kern_path_locked",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/quota/quota.c:quotactl_block",
        "ipc/mqueue.c:__do_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/xattr.c:io_setxattr",
        "io_uring/xattr.c:io_fsetxattr",
        "io_uring/xattr.c:io_getxattr",
        "io_uring/xattr.c:io_fgetxattr",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_link_cleanup",
        "io_uring/fs.c:io_linkat_prep",
        "io_uring/fs.c:io_symlinkat_prep",
        "io_uring/fs.c:io_mkdirat_cleanup",
        "io_uring/fs.c:io_unlinkat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_cleanup",
        "io_uring/fs.c:io_renameat_prep",
        "io_uring/openclose.c:io_open_cleanup",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/openclose.c:io_openat2",
        "io_uring/statx.c:io_statx_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029056,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493402304,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__arm64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:__arm64_sys_sysfs",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__arm64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493402304,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226988436,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:open_exec",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226988436,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286959360,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286959360,
      "name": "putname",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273114412,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:open_exec",
        "fs/exec.c:__se_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_parentat",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__se_sys_mq_unlink",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273114412,
      "name": "putname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581890320,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890320,
      "name": "putname",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827920,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827920,
      "name": "putname",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581881632,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881632,
      "name": "putname",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void putname(struct filename * name)
```

```json
{
  "name": "putname",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951136,
      "name": "putname",
      "external": true,
      "loc": "fs/namei.c:248",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/auditsc.c:__audit_syscall_exit",
        "kernel/auditsc.c:__audit_free",
        "kernel/bpf/inode.c:bpf_obj_get_user",
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/open.c:do_sys_open",
        "fs/open.c:filp_open",
        "fs/exec.c:open_exec",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_renameat2",
        "fs/namei.c:do_symlinkat",
        "fs/namei.c:do_unlinkat",
        "fs/namei.c:do_rmdir",
        "fs/namei.c:filename_create",
        "fs/namei.c:do_file_open_root",
        "fs/namei.c:filename_mountpoint",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:kern_path_locked",
        "fs/namei.c:filename_lookup",
        "fs/filesystems.c:fs_index",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/quota/quota.c:kernel_quotactl",
        "ipc/mqueue.c:__ia32_sys_mq_unlink",
        "ipc/mqueue.c:__x64_sys_mq_unlink",
        "ipc/mqueue.c:do_mq_open",
        "ipc/mqueue.c:do_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951136,
      "name": "putname",
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
