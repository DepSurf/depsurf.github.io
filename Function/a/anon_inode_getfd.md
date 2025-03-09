# Function: <code>anon_inode_getfd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298512,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/signalfd.c:SyS_signalfd",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/timerfd.c:SyS_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298512,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464736,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464736,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545488,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:SyS_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545488,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599408,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:SyS_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599408,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743744,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/signalfd.c:SyS_signalfd",
        "fs/timerfd.c:SyS_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743744,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912320,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:139",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912320,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996688,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:121",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996688,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133248,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133248,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210400,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210400,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446896,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/syscall.c:bpf_link_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446896,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503568,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503568,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531104,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:197",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531104,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847168,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:197",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__do_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847168,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408848,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:226",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408848,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995792,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:226",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995792,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584220464,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:226",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220464,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435072,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:234",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "security/landlock/syscalls.c:__do_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435072,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493773616,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vm_ioctl",
        "virt/kvm/kvm_main.c:kvm_vm_ioctl",
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__arm64_sys_fspick",
        "fs/fsopen.c:__arm64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init",
        "fs/timerfd.c:__arm64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__arm64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493773616,
      "name": "anon_inode_getfd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227289452,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/signalfd.c:do_signalfd4",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227289452,
      "name": "anon_inode_getfd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287386336,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287386336,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273370422,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__se_sys_fspick",
        "fs/fsopen.c:__se_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273370422,
      "name": "anon_inode_getfd",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179136,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179136,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116768,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116768,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169616,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169616,
      "name": "anon_inode_getfd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int anon_inode_getfd(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245824,
      "name": "anon_inode_getfd",
      "external": true,
      "loc": "fs/anon_inodes.c:125",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_create",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/bpf/btf.c:btf_new_fd",
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick",
        "fs/fsopen.c:__ia32_sys_fsopen",
        "fs/fsopen.c:__x64_sys_fsopen",
        "fs/notify/inotify/inotify_user.c:do_inotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/eventfd.c:do_eventfd",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245824,
      "name": "anon_inode_getfd",
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
