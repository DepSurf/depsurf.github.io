# Function: <code>skip_spaces</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582980752,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:438",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980752,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269952,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:438",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/params.c:parse_args",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269952,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583388720,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:438",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/params.c:parse_args",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388720,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588245232,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:438",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/label.c:aa_label_parse",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245232,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588796656,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:439",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/label.c:aa_label_parse",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796656,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589174768,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:439",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174768,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589404688,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:440",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404688,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589860528,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:482",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkg_conf_prep",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860528,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590086016,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086016,
      "name": "skip_spaces",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585083840,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:525",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:do_proc_douintvec_w",
        "kernel/sysctl.c:do_proc_douintvec_w",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:xbc_init",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083840,
      "name": "skip_spaces",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585233008,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:522",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:do_proc_douintvec_w",
        "kernel/sysctl.c:do_proc_douintvec_w",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:xbc_init",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233008,
      "name": "skip_spaces",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585115888,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:522",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:xbc_init",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115888,
      "name": "skip_spaces",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585564576,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:523",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:xbc_init",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564576,
      "name": "skip_spaces",
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586106167,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string_helpers.c:807",
      "file": "lib/string_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string_helpers.c:strim"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_separate_filter",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103232,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587091479,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string_helpers.c:851",
      "file": "lib/string_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string_helpers.c:strim"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_separate_filter",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "mm/vmscan.c:lru_gen_seq_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088240,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587351591,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string_helpers.c:851",
      "file": "lib/string_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string_helpers.c:strim"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_separate_filter",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_user.c:user_event_create",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "mm/vmscan.c:lru_gen_seq_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587348160,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587637815,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string_helpers.c:868",
      "file": "lib/string_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string_helpers.c:strim"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_separate_filter",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_trigger.c:trigger_process_regex",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_user.c:user_event_create",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "mm/vmscan.c:lru_gen_seq_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:do_setattr",
        "block/blk-cgroup.c:blkg_conf_open_bdev",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/bootconfig.c:xbc_parse_tree",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "lib/bootconfig.c:__xbc_parse_value",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/md/md.c:bitmap_store",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_device_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634288,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503865148,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string.c:strim"
      ],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863808,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236491608,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236491608,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297722688,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297722688,
      "name": "skip_spaces",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279759574,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759574,
      "name": "skip_spaces",
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
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589688272,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688272,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589414064,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414064,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590131648,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131648,
      "name": "skip_spaces",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
char * skip_spaces(const char * str)
```

```json
{
  "name": "skip_spaces",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590182032,
      "name": "skip_spaces",
      "external": true,
      "loc": "lib/string.c:484",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/params.c:parse_args",
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:proc_setgroups_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lib.c:aa_split_fqname",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/media/cec/cec-core.c:cec_error_inj_write",
        "drivers/md/dm-init.c:str_field_delimit",
        "drivers/md/dm-table.c:dm_split_args",
        "lib/cmdline.c:next_arg",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182032,
      "name": "skip_spaces",
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
