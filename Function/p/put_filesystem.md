# Function: <code>put_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119222,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:41",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:SyS_sysfs"
      ],
      "caller_func": [
        "kernel/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119408,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284950,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:41",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:SyS_sysfs"
      ],
      "caller_func": [
        "kernel/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285136,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581363366,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:41",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:SyS_sysfs"
      ],
      "caller_func": [
        "kernel/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363552,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581418819,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:42",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:SyS_sysfs"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418912,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581560375,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:43",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:SyS_sysfs"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560480,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716826,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:43",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717152,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581803546,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:43",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_mount",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mnt_init",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803872,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922401,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922736,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581994801,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995136,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582228628,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229184,
      "name": "put_filesystem",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582277028,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277584,
      "name": "put_filesystem",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582302563,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303120,
      "name": "put_filesystem",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582621603,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_root",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622176,
      "name": "put_filesystem",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583157486,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_nodev_root",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157584,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731342,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_nodev_root",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731504,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583948382,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_nodev_root",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948544,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584155822,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_nodev_root",
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_new_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155984,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493511116,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493512672,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227066468,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:__se_sys_sysfs"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227066804,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287075824,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:__se_sys_sysfs"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287076240,
      "name": "put_filesystem",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273181940,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:__se_sys_sysfs"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__se_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273182178,
      "name": "put_filesystem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963537,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963872,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581901105,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901440,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954817,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955152,
      "name": "put_filesystem",
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
void put_filesystem(struct file_system_type * fs)
```

```json
{
  "name": "put_filesystem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582025249,
      "name": "put_filesystem",
      "external": true,
      "loc": "fs/filesystems.c:44",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:get_fs_type",
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cpuset_init_fs_context",
        "kernel/trace/trace.c:trace_automount",
        "fs/super.c:deactivate_locked_super",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/fs_context.c:put_fs_context",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "security/tomoyo/mount.c:tomoyo_mount_acl",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025456,
      "name": "put_filesystem",
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
