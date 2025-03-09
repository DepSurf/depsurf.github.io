# Function: <code>dec_ucount</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556304,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:213",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/cgroup.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556304,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542960,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:218",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542960,
      "name": "dec_ucount",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569680,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:218",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569680,
      "name": "dec_ucount",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597856,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:219",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597856,
      "name": "dec_ucount",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634960,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:219",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634960,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659792,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659792,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696864,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696864,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737584,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:215",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737584,
      "name": "dec_ucount",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717536,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:215",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717536,
      "name": "dec_ucount",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724928,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:252",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724928,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804304,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:250",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804304,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914000,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:256",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914000,
      "name": "dec_ucount",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068080,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:252",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068080,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121456,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:252",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121456,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167040,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:253",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:free_time_ns",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark",
        "ipc/namespace.c:free_ipc",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167040,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490877760,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490877760,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224894660,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224894660,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283710624,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283710624,
      "name": "dec_ucount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271530360,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271530360,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673184,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673184,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601520,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601520,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670416,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670416,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704528,
      "name": "dec_ucount",
      "external": true,
      "loc": "kernel/ucount.c:212",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns",
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704528,
      "name": "dec_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void dec_ucount(struct ucounts * ucounts, enum ucount_type type)
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
