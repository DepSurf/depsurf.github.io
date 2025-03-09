# Function: <code>unregister_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485344,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1567",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/devpts/inode.c:init_devpts_fs",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485344,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669872,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1573",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669872,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758096,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1579",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758096,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581812256,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1643",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812256,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961808,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1644",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961808,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148416,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1646",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148416,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243376,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1646",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243376,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406928,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406928,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505888,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505888,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582814687,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1656",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810944,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071582811104,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582888399,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1656",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884656,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071582884816,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582916863,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1660",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912896,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071582913056,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583251471,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1660",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247408,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071583247568,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751078,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1729",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "drivers/char/hpet.c:hpet_init",
        "drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743920,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583744096,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584366758,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1728",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "drivers/char/hpet.c:hpet_init",
        "drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360352,
      "name": "unregister_sysctl_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584360544,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584590096,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1519",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "drivers/char/hpet.c:hpet_init",
        "drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "drivers/hv/hv_common.c:hv_common_free",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590096,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584821744,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1515",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "drivers/char/hpet.c:hpet_init",
        "drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "drivers/hv/hv_common.c:hv_common_free",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821744,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494132528,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494132528,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227581300,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227581300,
      "name": "unregister_sysctl_table",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287805456,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287805456,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273613838,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273613838,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474624,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474624,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411856,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "drivers/hv/vmbus_drv.c:vmbus_exit",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411856,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465104,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465104,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void unregister_sysctl_table(struct ctl_table_header * header)
```

```json
{
  "name": "unregister_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544368,
      "name": "unregister_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1673",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_clear_itmt_support",
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/sched/debug.c:unregister_sched_domain_sysctl",
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "ipc/mqueue.c:init_mqueue_fs",
        "drivers/char/hpet.c:hpet_init",
        "drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl",
        "drivers/cdrom/cdrom.c:cdrom_exit",
        "drivers/md/md.c:md_exit",
        "net/sysctl_net.c:unregister_net_sysctl_table",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544368,
      "name": "unregister_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
