# Function: <code>clear_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005232,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "mm/mempolicy.c:copy_nodes_to_user",
        "mm/mempolicy.c:compat_SyS_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005232,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295712,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "mm/mempolicy.c:compat_SyS_get_mempolicy",
        "mm/mempolicy.c:copy_nodes_to_user",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295712,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414576,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414576,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271440,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "arch/x86/kernel/ldt.c:sys_modify_ldt",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271440,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588827184,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:SyS_modify_ldt",
        "arch/x86/kernel/ldt.c:SyS_modify_ldt",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588827184,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205280,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205280,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446864,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446864,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904768,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904768,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130752,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130752,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135104,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:51",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_ip_fixup",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:copy_nodes_to_user",
        "fs/notify/inotify/inotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_info_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135104,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286448,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:51",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_ip_fixup",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:copy_nodes_to_user",
        "fs/notify/inotify/inotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_info_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286448,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170176,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:51",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_info_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170176,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623872,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:51",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623872,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783008,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:49",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl.c:keyctl_capabilities",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783008,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183361,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917660,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124378,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583957907,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971743,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157470,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169923,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373902,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585484160,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585506837,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057425,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929387,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592147206,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592574441,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:121",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579187681,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967549,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583334747,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181345,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195266,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584385105,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584397855,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585715649,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585738485,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587318178,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590238780,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592570512,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593005168,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579216897,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006957,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583570779,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395345,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409234,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599725,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584612072,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585962769,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585985733,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603379,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579756,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592186949,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/gpu/drm/drm_ioc32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593315136,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593756436,
      "name": "clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:188",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:copy_params",
        "drivers/md/dm-ioctl.c:copy_params"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224801796,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3226310592,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 3227268104,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227276612,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227418728,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 3227432692,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf_fdpic.c:elf_fdpic_map_file",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_map_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3227439140,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "fs/binfmt_flat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_flat.c:load_flat_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3228473176,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228498640,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 3229445756,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 3231348008,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3233284888,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233709504,
      "name": "clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:577",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227412272,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282261488,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283579064,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285705280,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286441420,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__se_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287358576,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287365904,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287590392,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287605976,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287824440,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288977408,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289012084,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290373300,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291875276,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294224944,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294726244,
      "name": "clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:406",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287589584,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 13835058055287605152,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271454894,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273351268,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273356814,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273491956,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446743936273495372,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "fs/binfmt_flat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_flat.c:load_flat_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273624156,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274344208,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274365212,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275183118,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "drivers/char/mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277604408,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277904018,
      "name": "clear_user",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:396",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273483348,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733008,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733008,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458688,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458688,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176384,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176384,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
long unsigned int clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226832,
      "name": "clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:50",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:read_ldt",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_ip_fixup",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/char/mem.c:read_mem",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226832,
      "name": "clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int clear_user(void * to, long unsigned int n)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int clear_user(void * to, long unsigned int n)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>void * to</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int n</code>
</li>
</ul>
</details>
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
