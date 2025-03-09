# Function: <code>match_string</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270512,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:642",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/power/charger-manager.c:cm_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270512,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389280,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:642",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/power/supply/charger-manager.c:cm_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389280,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245712,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:642",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245712,
      "name": "match_string",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797136,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:643",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797136,
      "name": "match_string",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175232,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:643",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175232,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405152,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:644",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405152,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860960,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:686",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860960,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086448,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086448,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585084272,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:737",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:parse_resource",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084272,
      "name": "match_string",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233440,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:734",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:parse_resource",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233440,
      "name": "match_string",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116304,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:734",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_parse_limits",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116304,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564992,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:735",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_parse_limits",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_role_switch_default_mode",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564992,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586106016,
      "name": "match_string",
      "external": true,
      "loc": "lib/string_helpers.c:885",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_parse_limits",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "fs/verity/measure.c:fsverity_get_digest",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_role_switch_default_mode",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106016,
      "name": "match_string",
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587091264,
      "name": "match_string",
      "external": true,
      "loc": "lib/string_helpers.c:929",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_parse_limits",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "lib/dynamic_debug.c:param_set_dyndbg_classnames",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_role_switch_default_mode",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091264,
      "name": "match_string",
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587351376,
      "name": "match_string",
      "external": true,
      "loc": "lib/string_helpers.c:929",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/rdma.c:parse_resource",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "lib/dynamic_debug.c:param_set_dyndbg_classnames",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_role_switch_default_mode",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/amd-pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351376,
      "name": "match_string",
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637600,
      "name": "match_string",
      "external": true,
      "loc": "lib/string_helpers.c:946",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/cgroup/rdma.c:parse_resource",
        "kernel/trace/trace.c:trace_set_options",
        "kernel/trace/trace_osnoise.c:osnoise_options_write",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest",
        "lib/dynamic_debug.c:param_set_dyndbg_classnames",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/acpi/scan.c:acpi_info_matches_ids",
        "drivers/base/property.c:fwnode_property_match_property_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_role_switch_default_mode",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_ssp_rate",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/amd-pstate.c:store_energy_performance_preference",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637600,
      "name": "match_string",
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503864840,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_set_by_name",
        "drivers/gpio/gpiolib-of.c:of_find_gpio",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock",
        "drivers/clk/rockchip/clk.c:rockchip_clk_register_branches",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503864840,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492228,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/gpio/gpiolib-of.c:of_find_gpio",
        "drivers/clk/rockchip/clk.c:rockchip_clk_register_branches",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/mfd/omap-usb-host.c:usbhs_omap_probe",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "sound/soc/soc-dapm.c:dapm_connect_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492228,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297723376,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:scanhex",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/gpio/gpiolib-of.c:of_find_gpio",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297723376,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760068,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/gpio/gpiolib-of.c:of_find_gpio",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/usb/common/common.c:of_usb_get_dr_mode_by_phy",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760068,
      "name": "match_string",
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688704,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688704,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414496,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414496,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132080,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132080,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int match_string(const const char * * array, size_t n, const char * string)
```

```json
{
  "name": "match_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182464,
      "name": "match_string",
      "external": true,
      "loc": "lib/string.c:688",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max",
        "kernel/trace/trace.c:trace_set_options",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/vmpressure.c:vmpressure_register_event",
        "mm/vmpressure.c:vmpressure_register_event",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/integrity/ima/ima_main.c:hash_setup",
        "drivers/pinctrl/pinmux.c:pinmux_map_to_setting",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/vfio/vfio.c:vfio_dev_viable",
        "drivers/usb/common/common.c:usb_get_dr_mode",
        "drivers/usb/common/common.c:usb_get_maximum_speed",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182464,
      "name": "match_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int match_string(const const char * * array, size_t n, const char * string)
```
</details>
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
