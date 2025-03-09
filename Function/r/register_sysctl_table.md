# Function: <code>register_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491984,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1502",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/core.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491984,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676720,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1508",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676720,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764864,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1514",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764864,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818992,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1578",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818992,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968560,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1579",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968560,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153312,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1581",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153312,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247920,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1580",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247920,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412576,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412576,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511536,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511536,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814784,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1588",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814784,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888496,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1588",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888496,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582916960,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1592",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916960,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251568,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1592",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251568,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751257,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1652",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_base"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751200,
      "name": "register_sysctl_table",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584366985,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1651",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_base"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_io.c:tty_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584366912,
      "name": "register_sysctl_table",
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494139248,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494139248,
      "name": "register_sysctl_table",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227587028,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/isa.c:register_isa_ports",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227587028,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287816240,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/idle.c:register_powersave_nap_sysctl",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287816240,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273618930,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273618930,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480272,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480272,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417504,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init",
        "drivers/hv/vmbus_drv.c:hv_acpi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417504,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470752,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470752,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```

```json
{
  "name": "register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551088,
      "name": "register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1605",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/sysctl.c:sysctl_init",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/ipc_sysctl.c:ipc_sysctl_init",
        "ipc/mq_sysctl.c:mq_register_sysctl_table",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/tty/tty_ldisc.c:tty_sysctl_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551088,
      "name": "register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct ctl_table_header * register_sysctl_table(struct ctl_table * table)
```
</details>
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
