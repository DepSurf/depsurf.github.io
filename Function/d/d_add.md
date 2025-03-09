# Function: <code>d_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "d_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581155224,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456328,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/base.c:proc_task_instantiate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464052,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473691,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480587,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482056,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/self.c:proc_setup_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482696,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/thread_self.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/thread_self.c:proc_setup_thread_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486818,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524249,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_pty_new"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998404,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/ecryptfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/ecryptfs/inode.c:ecryptfs_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108349,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_ctl_add_dentry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122010,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/pstore/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pstore/inode.c:pstore_mkfile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128724,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295710,
      "name": "d_add",
      "external": false,
      "loc": "include/linux/dcache.h:285",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258784,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2553",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258784,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581336800,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2562",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336800,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392064,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2592",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/configfs/inode.c:configfs_create",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392064,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532640,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2604",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/configfs/inode.c:configfs_create",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532640,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683712,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2624",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/inode.c:configfs_create",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683712,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769216,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2605",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/inode.c:configfs_create",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769216,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886448,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/inode.c:configfs_create",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886448,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958992,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958992,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194032,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2696",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_perm_files",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194032,
      "name": "d_add",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582241552,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2703",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:mknod_ptmx",
        "fs/ecryptfs/inode.c:ecryptfs_lookup_interpose",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_perm_files",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241552,
      "name": "d_add",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267280,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2730",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267280,
      "name": "d_add",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585024,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2731",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585024,
      "name": "d_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583118384,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2756",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118384,
      "name": "d_add",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688576,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2811",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688576,
      "name": "d_add",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583906464,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2811",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583906464,
      "name": "d_add",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113184,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2635",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:create_default_group",
        "fs/configfs/dir.c:configfs_lookup",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/devpts/inode.c:devpts_fill_super",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/tracefs/event_inode.c:eventfs_root_lookup",
        "fs/tracefs/event_inode.c:eventfs_root_lookup",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_classes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113184,
      "name": "d_add",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493459656,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493459656,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227031256,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227031256,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287019360,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287019360,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273140278,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273140278,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927728,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927728,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865312,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865312,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919040,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919040,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void d_add(struct dentry * entry, struct inode * inode)
```

```json
{
  "name": "d_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993760,
      "name": "d_add",
      "external": true,
      "loc": "fs/dcache.c:2675",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_fill_super",
        "fs/proc/self.c:proc_setup_self",
        "fs/proc/thread_self.c:proc_setup_thread_self",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/devpts/inode.c:devpts_pty_new",
        "fs/ecryptfs/inode.c:ecryptfs_lookup",
        "fs/fuse/control.c:fuse_ctl_add_dentry",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/efivarfs/super.c:efivarfs_callback",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_fill_super",
        "security/selinux/selinuxfs.c:sel_make_dir",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993760,
      "name": "d_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void d_add(struct dentry * entry, struct inode * inode)
```
</details>
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
