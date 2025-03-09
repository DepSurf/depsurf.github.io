# Function: <code>x86_match_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112576,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:31",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112576,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112384,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:31",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112384,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579110928,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:31",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110928,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579102640,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:31",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102640,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114432,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114432,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121088,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121088,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126880,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126880,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136656,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136656,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138576,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138576,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154352,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154352,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151600,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151600,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157968,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157968,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:force_storage_d3",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061854,
      "name": "x86_match_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579187360,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:force_storage_d3",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593828366,
      "name": "x86_match_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579234960,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:force_storage_d3",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595960630,
      "name": "x86_match_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579294272,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:force_storage_d3",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596477937,
      "name": "x86_match_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579300688,
      "name": "x86_match_cpu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:37",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:force_storage_d3",
        "drivers/acpi/x86/utils.c:acpi_device_override_status",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params",
        "drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597373716,
      "name": "x86_match_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579330320,
      "name": "x86_match_cpu",
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138944,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138944,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070080,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070080,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138496,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138496,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```

```json
{
  "name": "x86_match_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143632,
      "name": "x86_match_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/match.c:32",
      "file": "arch/x86/kernel/cpu/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/cpu/common.c:cpu_matches",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/x86/utils.c:acpi_device_always_present",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init",
        "drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init",
        "arch/x86/power/cpu.c:pm_check_save_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143632,
      "name": "x86_match_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct x86_cpu_id * x86_match_cpu(const struct x86_cpu_id * match)
```
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
