# Function: <code>kstrndup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597504,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:84",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/argv_split.c:argv_split",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597504,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698496,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:84",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/argv_split.c:argv_split",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698496,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764272,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:84",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/cgroup.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/argv_split.c:argv_split",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764272,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800464,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:89",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800464,
      "name": "kstrndup",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889168,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:89",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_function_set_filter_cb",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889168,
      "name": "kstrndup",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025088,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:89",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025088,
      "name": "kstrndup",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102608,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:82",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102608,
      "name": "kstrndup",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:89",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170106,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581166864,
      "name": "kstrndup",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228152,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581224656,
      "name": "kstrndup",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/argv_split.c:argv_split",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415931,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581412224,
      "name": "kstrndup",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:97",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/dynamic_debug.c:dynamic_debug_exec_queries",
        "lib/argv_split.c:argv_split",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325431,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581454896,
      "name": "kstrndup",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:97",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/dynamic_debug.c:dynamic_debug_exec_queries",
        "lib/argv_split.c:argv_split",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267427,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581475776,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:97",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "lib/dynamic_debug.c:dynamic_debug_exec_queries",
        "lib/argv_split.c:argv_split",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592192634,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581729840,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:98",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:__ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "lib/dynamic_debug.c:dynamic_debug_exec_queries",
        "lib/argv_split.c:argv_split",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/driver.c:driver_set_override",
        "drivers/base/driver.c:driver_set_override",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593968536,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582109456,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584816,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:98",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:__ext4_fill_super",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/driver.c:driver_set_override",
        "drivers/base/driver.c:driver_set_override",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584816,
      "name": "kstrndup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791936,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:99",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:__ext4_fill_super",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/driver.c:driver_set_override",
        "drivers/base/driver.c:driver_set_override",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791936,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966976,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:99",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:__ftrace_function_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:parse_apply_sb_mount_options",
        "security/smack/smack_access.c:smk_parse_smack",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:reset_method_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/driver.c:driver_set_override",
        "drivers/base/driver.c:driver_set_override",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_table_entry",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966976,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492613336,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/amba/bus.c:driver_override_store",
        "drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492613336,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226465052,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/amba/bus.c:driver_override_store",
        "drivers/base/platform.c:driver_override_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226465052,
      "name": "kstrndup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285930400,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285930400,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272640000,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272640000,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197000,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581193504,
      "name": "kstrndup",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "drivers/hv/vmbus_drv.c:driver_override_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143752,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581140256,
      "name": "kstrndup",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188200,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581184704,
      "name": "kstrndup",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
char * kstrndup(const char * s, size_t max, gfp_t gfp)
```

```json
{
  "name": "kstrndup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kstrndup",
      "external": true,
      "loc": "mm/util.c:96",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/wakelock.c:wakelock_lookup_add",
        "kernel/trace/trace_events_filter.c:ftrace_profile_set_filter",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/ext4/super.c:ext4_fill_super",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci-sysfs.c:driver_override_store",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_create",
        "drivers/base/platform.c:driver_override_store",
        "drivers/nvdimm/namespace_devs.c:alt_name_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/input/misc/uinput.c:uinput_dev_setup",
        "drivers/md/dm-init.c:dm_init_init",
        "drivers/md/dm-init.c:dm_parse_devices",
        "drivers/remoteproc/remoteproc_sysfs.c:firmware_store",
        "lib/argv_split.c:argv_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251520,
      "name": "kstrndup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581247952,
      "name": "kstrndup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
