# Function: <code>strreplace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982032,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:950",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982032,
      "name": "strreplace",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271216,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:947",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271216,
      "name": "strreplace",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389984,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:947",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389984,
      "name": "strreplace",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588246112,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:973",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246112,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797536,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1040",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797536,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175632,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1040",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175632,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405552,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1041",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405552,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861360,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1103",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861360,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086848,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086848,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585084704,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1141",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084704,
      "name": "strreplace",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233840,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1137",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233840,
      "name": "strreplace",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116672,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1137",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116672,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565392,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1153",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565392,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586103616,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string_helpers.c:944",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103616,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088592,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string_helpers.c:988",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088592,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
char * strreplace(char * str, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587348512,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string_helpers.c:990",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/base/core.c:device_get_devnode",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587348512,
      "name": "strreplace",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strreplace(char * str, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587637528,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string_helpers.c:1007",
      "file": "lib/string_helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/string_helpers.c:kstrdup_and_replace"
      ],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/efivarfs/super.c:efivarfs_callback",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634640,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503864520,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503864520,
      "name": "strreplace",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492712,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492712,
      "name": "strreplace",
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297723696,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297723696,
      "name": "strreplace",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760912,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760912,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689104,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689104,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414896,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414896,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132480,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132480,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
char * strreplace(char * s, char old, char new)
```

```json
{
  "name": "strreplace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182864,
      "name": "strreplace",
      "external": true,
      "loc": "lib/string.c:1084",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklisted",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs",
        "drivers/thermal/thermal_hwmon.c:thermal_hwmon_lookup_by_type",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182864,
      "name": "strreplace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * str</code>
</li>
<li>
<b>Param removed. </b>
<code>char * s</code>
</li>
</ul>
</details>
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
