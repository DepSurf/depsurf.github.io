# Function: <code>inc_ucount</code>

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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555776,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:190",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555776,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542432,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:195",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542432,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569152,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:195",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569152,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597312,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:196",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597312,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634432,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:196",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634432,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659264,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659264,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696336,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696336,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737440,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:192",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737440,
      "name": "inc_ucount",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717392,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:192",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717392,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724784,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:229",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724784,
      "name": "inc_ucount",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804144,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:227",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804144,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913824,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:233",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913824,
      "name": "inc_ucount",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067728,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:229",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067728,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121104,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:229",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121104,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166688,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:230",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:clone_uts_ns",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_new_watch",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166688,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490877488,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490877488,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224894032,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224894032,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283709776,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283709776,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271529788,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271529788,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672656,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672656,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601008,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601008,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669888,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669888,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
```

```json
{
  "name": "inc_ucount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704032,
      "name": "inc_ucount",
      "external": true,
      "loc": "kernel/ucount.c:189",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/utsname.c:copy_utsname",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/inotify/inotify_user.c:inotify_update_watch",
        "ipc/namespace.c:copy_ipcs",
        "net/core/net_namespace.c:copy_net_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704032,
      "name": "inc_ucount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
struct ucounts * inc_ucount(struct user_namespace * ns, kuid_t uid, enum ucount_type type)
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
