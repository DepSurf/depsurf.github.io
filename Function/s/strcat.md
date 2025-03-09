# Function: <code>strcat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strcat(char * dest, const char * src)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980368,
      "name": "strcat",
      "external": true,
      "loc": "lib/string.c:245",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980368,
      "name": "strcat",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
char * strcat(char * dest, const char * src)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269584,
      "name": "strcat",
      "external": true,
      "loc": "lib/string.c:245",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269584,
      "name": "strcat",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
char * strcat(char * dest, const char * src)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388352,
      "name": "strcat",
      "external": true,
      "loc": "lib/string.c:245",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388352,
      "name": "strcat",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156037,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:216",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger",
        "kernel/params.c:param_attr_show",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243808,
      "name": "strcat",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170949,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:248",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795232,
      "name": "strcat",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579182493,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:249",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173424,
      "name": "strcat",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579171837,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:256",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403344,
      "name": "strcat",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184470,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:263",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859376,
      "name": "strcat",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186758,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085168,
      "name": "strcat",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207222,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:310",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082960,
      "name": "strcat",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579202614,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:304",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232128,
      "name": "strcat",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204986,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:41",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115008,
      "name": "strcat",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579241546,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:41",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563680,
      "name": "strcat",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(const char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292919,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:93",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586716816,
      "name": "strcat",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(const char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358854,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:163",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595878896,
      "name": "strcat",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(const char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367830,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:428",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596396272,
      "name": "strcat",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(const char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579399334,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:373",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597291504,
      "name": "strcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491964688,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/clk/zynqmp/clkc.c:zynqmp_register_clocks",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863128,
      "name": "strcat",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225899200,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "sound/sound_core.c:register_sound_special_device",
        "sound/core/init.c:snd_component_add",
        "sound/core/init.c:snd_component_add",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236490492,
      "name": "strcat",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285077744,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297721344,
      "name": "strcat",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
char * strcat(char * dest, const char * src)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279759260,
      "name": "strcat",
      "external": true,
      "loc": "lib/string.c:282",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/ipv4/devinet.c:inetdev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759260,
      "name": "strcat",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185942,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687424,
      "name": "strcat",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579120278,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/ip_tunnel.c:__ip_tunnel_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413216,
      "name": "strcat",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186678,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130800,
      "name": "strcat",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
char * strcat(char * p, const char * q)
```

```json
{
  "name": "strcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191990,
      "name": "strcat",
      "external": true,
      "loc": "include/linux/string.h:284",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/base/memory.c:print_allowed_zone",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181184,
      "name": "strcat",
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * p</code>
</li>
<li>
<b>Param added. </b>
<code>const char * q</code>
</li>
<li>
<b>Param removed. </b>
<code>char * dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * src</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * p</code> ➡️ <code>const char * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char * src</code>
</li>
<li>
<b>Param removed. </b>
<code>char * p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * q</code>
</li>
</ul>
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
