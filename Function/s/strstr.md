# Function: <code>strstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981520,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:809",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_matches",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981520,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270704,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:806",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270704,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389472,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:806",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/policy.c:aa_null_profile",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389472,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245888,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:832",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/security.c:security_setprocattr",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245888,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797312,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:899",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/label.c:aa_label_parse",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797312,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175408,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:899",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175408,
      "name": "strstr",
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405328,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:900",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405328,
      "name": "strstr",
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861136,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:962",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861136,
      "name": "strstr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086624,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086624,
      "name": "strstr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585084480,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:1000",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084480,
      "name": "strstr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233648,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:996",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:__list_lookup_parent",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233648,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116496,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:996",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116496,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565184,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:1012",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565184,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718048,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:825",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718048,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595880384,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:751",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595880384,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596397616,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:749",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:tr_needs_alloc_snapshot",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_user.c:user_event_set_print_fmt",
        "kernel/trace/trace_events_user.c:user_field_format",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596397616,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597292848,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:734",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:tr_needs_alloc_snapshot",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events.c:trace_create_new_event",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events.c:test_event_printk",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_synth.c:__synth_event_show",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_hist.c:trace_action_create",
        "kernel/trace/trace_events_user.c:user_event_set_print_fmt",
        "kernel/trace/trace_events_user.c:user_field_format",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_add_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_set_mode",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597292848,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510870592,
      "name": "strstr",
      "external": true,
      "loc": "drivers/firmware/efi/libstub/string.c:18",
      "file": "drivers/firmware/efi/libstub/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/arm64/kernel/kaslr.c:kaslr_early_init",
        "drivers/firmware/efi/libstub/arm-stub.c:efi_entry",
        "drivers/firmware/efi/libstub/efi-stub-helper.c:handle_cmdline_files",
        "drivers/firmware/efi/libstub/efi-stub-helper.c:handle_cmdline_files",
        "drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options",
        "drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options",
        "drivers/firmware/efi/libstub/efi-stub-helper.c:efi_parse_options",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865216,
      "name": "strstr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492476,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches",
        "sound/core/init.c:snd_component_add",
        "sound/soc/soc-core.c:fmt_single_name",
        "sound/soc/soc-dapm.c:snd_soc_dapm_link_dai_widgets",
        "sound/soc/soc-ops.c:snd_soc_info_volsw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492476,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297724288,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/powerpc/kernel/udbg.c:register_early_udbg_console",
        "arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init",
        "arch/powerpc/kernel/module_64.c:module_frob_arch_sections",
        "arch/powerpc/kernel/legacy_serial.c:check_legacy_serial_console",
        "arch/powerpc/mm/numa.c:early_numa",
        "arch/powerpc/mm/numa.c:early_numa",
        "arch/powerpc/mm/numa.c:early_numa",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/tty/hvc/hvc_vio.c:hvc_vio_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297724288,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760424,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760424,
      "name": "strstr",
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
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688880,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688880,
      "name": "strstr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414672,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414672,
      "name": "strstr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132256,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132256,
      "name": "strstr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
char * strstr(const char * s1, const char * s2)
```

```json
{
  "name": "strstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182640,
      "name": "strstr",
      "external": true,
      "loc": "lib/string.c:943",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:init_rootfs",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/common.c:print_cpu_info",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "kernel/resource.c:strict_iomem",
        "kernel/resource.c:strict_iomem",
        "kernel/trace/ftrace.c:ftrace_match",
        "kernel/trace/trace.c:err_pos",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_filter.c:filter_assign_type",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "mm/memblock.c:early_memblock",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/common.c:tomoyo_find_yesno",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/util.c:tomoyo_permstr",
        "security/apparmor/lib.c:aa_policy_init",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces",
        "drivers/acpi/acpica/dbutils.c:acpi_db_match_argument",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "drivers/firmware/dmi_scan.c:dmi_name_in_vendors",
        "drivers/firmware/dmi_scan.c:dmi_name_in_serial",
        "drivers/firmware/dmi_scan.c:dmi_matches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182640,
      "name": "strstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
