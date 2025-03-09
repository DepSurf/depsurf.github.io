# Function: <code>__put_user_ns</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580092498,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:200",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/super.c:destroy_super",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089904,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098206,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:201",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/super.c:destroy_super",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095552,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150974,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:215",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147760,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580208901,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:215",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207568,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261157,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:215",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259824,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312190,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310864,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580361022,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359696,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436159,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435856,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423965,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422896,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580428376,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:210",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/namespace.c:free_vfsmnt",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427280,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580592168,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:226",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/ucount.c:put_ucounts",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/namespace.c:free_vfsmnt",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591072,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580794485,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:231",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/ucount.c:put_ucounts",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/namespace.c:free_vfsmnt",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793280,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581079237,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:231",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/ucount.c:put_ucounts",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/namespace.c:free_vfsmnt",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "security/apparmor/notify.c:build_unotif",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077952,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581170549,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:231",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/ucount.c:put_ucounts",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:finish_mount_kattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "security/apparmor/notify.c:build_v3_unotif",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169264,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581275065,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:234",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/cred.c:put_cred_rcu",
        "kernel/ucount.c:put_ucounts",
        "kernel/time/namespace.c:free_time_ns",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/super.c:destroy_super_work",
        "fs/exec.c:would_dump",
        "fs/namespace.c:finish_mount_kattr",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "fs/fuse/inode.c:delayed_release",
        "ipc/mqueue.c:mq_init_ns",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:free_ipc",
        "security/apparmor/notify.c:build_v3_unotif",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273760,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491624452,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491620456,
      "name": "__put_user_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225577544,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225575972,
      "name": "__put_user_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284614896,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284612752,
      "name": "__put_user_ns",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272022268,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272020682,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329822,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328496,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580277086,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275760,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580321070,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319744,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __put_user_ns(struct user_namespace * ns)
```

```json
{
  "name": "__put_user_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580376094,
      "name": "__put_user_ns",
      "external": true,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context",
        "kernel/fork.c:__mmdrop",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/exec.c:would_dump",
        "fs/namespace.c:free_mnt_ns",
        "fs/fs_context.c:put_fs_context",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374688,
      "name": "__put_user_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __put_user_ns(struct user_namespace * ns)
```
</details>
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
