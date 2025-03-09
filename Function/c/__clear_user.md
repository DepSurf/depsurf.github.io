# Function: <code>__clear_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005088,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:15",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "fs/signalfd.c:signalfd_copyinfo",
        "fs/compat.c:put_compat_statfs",
        "fs/compat.c:put_compat_statfs64",
        "arch/x86/lib/usercopy_64.c:clear_user",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005088,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295568,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:15",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "fs/signalfd.c:signalfd_copyinfo",
        "fs/compat.c:put_compat_statfs64",
        "fs/compat.c:put_compat_statfs",
        "arch/x86/lib/usercopy_64.c:clear_user",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295568,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414432,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:15",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "fs/signalfd.c:signalfd_copyinfo",
        "fs/compat.c:put_compat_statfs64",
        "fs/compat.c:put_compat_statfs",
        "arch/x86/lib/usercopy_64.c:clear_user",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414432,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271360,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:16",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "fs/signalfd.c:signalfd_copyinfo",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271360,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588827104,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:16",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "fs/signalfd.c:signalfd_copyinfo",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588827104,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205200,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:16",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205200,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446784,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:16",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446784,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904688,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904688,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130672,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130672,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585134944,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134944,
      "name": "__clear_user",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286288,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286288,
      "name": "__clear_user",
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170016,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170016,
      "name": "__clear_user",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623712,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623712,
      "name": "__clear_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782800,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782800,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
  "name": "__clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183405,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249615,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917689,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124419,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958124,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971774,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157501,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169954,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373933,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585484191,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585506866,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057527,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929425,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592147236,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592574797,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:94",
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
  "name": "__clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579187711,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256260,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967577,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583334776,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181364,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195333,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584385114,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584397864,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:padzero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585715670,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585738560,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587318198,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590238843,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592570541,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593005203,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
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
  "name": "__clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579216927,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:read_default_ldt",
        "arch/x86/kernel/ldt.c:read_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286148,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006985,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583570808,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:copy_nodes_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395364,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:copy_event_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409301,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599794,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584612141,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585962790,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585985808,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603396,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579819,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592186970,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/gpu/drm/drm_ioc32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593315165,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_get_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593756471,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int __clear_user(void * to, long unsigned int n)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490212612,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490495420,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "arch/arm64/kvm/guest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490753384,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492435448,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493014616,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493744928,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493753204,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493959416,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493973936,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336494146824,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ]
    },
    {
      "addr": 18446603336495079724,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495108504,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496121080,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498722500,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500772620,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501204324,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:420",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493949352,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446603336493964424,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446603336494144616,
      "name": "__clear_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__clear_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224801828,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:copy_siginfo_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3226310764,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 3227268208,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227276632,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227418760,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 3227432732,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf_fdpic.c:elf_fdpic_map_file",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_map_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3227439620,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "fs/binfmt_flat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_flat.c:load_flat_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3228473216,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228498664,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_query"
      ],
      "caller_func": []
    },
    {
      "addr": 3229445916,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 3231348032,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3233286048,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233709788,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:551",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282261488,
      "name": "__clear_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:418",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clear_user",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:copy_siginfo_to_user",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_flat.c:load_flat_file",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279789432,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589732928,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589732928,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458608,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458608,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176304,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176304,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```

```json
{
  "name": "__clear_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226752,
      "name": "__clear_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:17",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/lib/usercopy_64.c:clear_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226752,
      "name": "__clear_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int __clear_user(void * addr, long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * to</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int n</code>
</li>
<li>
<b>Param removed. </b>
<code>void * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int __clear_user(void * addr, long unsigned int size)
```
</details>
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
