# Function: <code>security_locked_down</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389328,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389328,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727296,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2979",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_one",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727296,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847488,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2997",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_one",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847488,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873328,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:3060",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_one",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873328,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237104,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:3068",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_one",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237104,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584843536,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:3146",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_check_unsafe",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module/signing.c:module_sig_check",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_init_dentry",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/integrity/ima/ima_policy.c:ima_appraise_signature",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843536,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545504,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:3126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_check_unsafe",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module/signing.c:module_sig_check",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_init_dentry",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/integrity/ima/ima_policy.c:ima_appraise_signature",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545504,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776160,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:5589",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_check_unsafe",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume_initcall",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module/signing.c:module_sig_check",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_init_dentry",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_fprobe.c:register_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "security/integrity/ima/ima_policy.c:ima_appraise_signature",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776160,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025152,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:5730",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/params.c:param_check_unsafe",
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume_initcall",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module/signing.c:module_sig_check",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_prepare_segments",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_init_dentry",
        "kernel/trace/trace.c:tracing_open_options",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_time_stamp_mode_open",
        "kernel/trace/trace.c:tracing_clock_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_trace_options_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_mark_open",
        "kernel/trace/trace.c:tracing_open_file_tr",
        "kernel/trace/trace.c:tracing_open_generic",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/trace/trace_kprobe.c:create_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_fprobe.c:register_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/bpf/helpers.c:bpf_base_func_proto",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_dir",
        "fs/tracefs/inode.c:tracefs_create_file",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "security/integrity/ima/ima_policy.c:ima_appraise_signature",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025152,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495139696,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "kernel/kexec.c:__arm64_sys_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495139696,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228527572,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__se_sys_kexec_load",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/debugfs/file.c:debugfs_locked_down",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_mmap_resource",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228527572,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289056176,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:xmon_is_locked_down",
        "arch/powerpc/xmon/xmon.c:xmon_is_locked_down",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__se_compat_sys_kexec_load",
        "kernel/kexec.c:__se_sys_kexec_load",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/debugfs/file.c:debugfs_locked_down",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/syscall.c:__se_sys_pciconfig_write",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289056176,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274389740,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/debugfs/file.c:debugfs_locked_down",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274389740,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358064,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358064,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295168,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295168,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341840,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341840,
      "name": "security_locked_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_locked_down(enum lockdown_reason what)
```

```json
{
  "name": "security_locked_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437024,
      "name": "security_locked_down",
      "external": true,
      "loc": "security/security.c:2608",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/module.c:load_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/trace/ftrace.c:ftrace_graph_notrace_open",
        "kernel/trace/ftrace.c:ftrace_graph_open",
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:register_tracer",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/debugfs/inode.c:debugfs_setattr",
        "fs/tracefs/inode.c:tracefs_create_file",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/proc.c:proc_bus_pci_mmap",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/acpi/osl.c:acpi_os_get_root_pointer",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/char/mem.c:open_port",
        "drivers/firmware/efi/efi.c:efivar_ssdt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437024,
      "name": "security_locked_down",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int security_locked_down(enum lockdown_reason what)
```
</details>
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
