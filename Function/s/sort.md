# Function: <code>sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006368,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:59",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:sanitize_e820_map",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/mm/extable.c:sort_extable",
        "arch/x86/mm/extable.c:sort_extable",
        "kernel/range.c:clean_sort_range",
        "kernel/range.c:sort_range",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006368,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296864,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:59",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:sanitize_e820_map",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296864,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583415728,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:59",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:sanitize_e820_map",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415728,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437456,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:61",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:set_groups",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437456,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617392,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:62",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:SyS_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617392,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833808,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:62",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833808,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917504,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:62",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917504,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097376,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:191",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097376,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584220592,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220592,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626544,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:266",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:sort_secondary",
        "kernel/bpf/btf.c:btf_check_sec_info",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626544,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744944,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:266",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:sort_secondary",
        "kernel/bpf/btf.c:btf_check_sec_info",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744944,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773088,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:266",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773088,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202976,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:266",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202976,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039584,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:281",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/fprobe.c:get_ftrace_locations",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:__btf_populate_kfunc_set",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/static_call_inline.c:__static_call_init",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/extable.c:sort_extable",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039584,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021888,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:281",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/fprobe.c:register_fprobe_syms",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/static_call_inline.c:__static_call_init",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021888,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276912,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:281",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/fprobe.c:register_fprobe_syms",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/static_call_inline.c:__static_call_init",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/group_cpus.c:alloc_nodes_groups",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276912,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sort(void * base, size_t num, size_t size, cmp_func_t cmp_func, swap_func_t swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587565648,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:281",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/mm/numa.c:numa_fill_memblks",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_dispatcher",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__do_sys_setgroups",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/fprobe.c:get_ftrace_locations",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/static_call_inline.c:__static_call_init",
        "kernel/jump_label.c:jump_label_add_module",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "lib/group_cpus.c:alloc_nodes_groups",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_power_verify",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos",
        "drivers/gpu/drm/drm_blend.c:drm_atomic_helper_crtc_normalize_zpos",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565648,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510869328,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/module-plts.c:module_frob_arch_sections",
        "drivers/firmware/efi/libstub/arm-stub.c:efi_get_virtmap",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__arm64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496093832,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229420872,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229420872,
      "name": "sort",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290336528,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/module_64.c:module_frob_arch_sections",
        "arch/powerpc/kernel/module_64.c:module_frob_arch_sections",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290336528,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275162742,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275162742,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189328,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189328,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124560,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124560,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173088,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173088,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void sort(void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func)
```

```json
{
  "name": "sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584277392,
      "name": "sort",
      "external": true,
      "loc": "lib/sort.c:271",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__update_table",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "kernel/range.c:sort_range",
        "kernel/range.c:clean_sort_range",
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/btf.c:btf_parse_hdr",
        "kernel/jump_label.c:jump_label_module_notify",
        "kernel/jump_label.c:jump_label_init",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/compat_ioctl.c:init_sys32_ioctl",
        "fs/ext4/fsmap.c:ext4_getfsmap",
        "security/apparmor/label.c:aa_vec_unique",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "lib/extable.c:sort_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277392,
      "name": "sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(const void *, const void *) cmp_func</code> ➡️ <code>cmp_func_t cmp_func</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*)(void *, void *, int) swap_func</code> ➡️ <code>swap_func_t swap_func</code>
</li>
</ul>
</details>
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
