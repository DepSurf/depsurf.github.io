# Function: <code>freq_qos_add_request</code>

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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921840,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921840,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966816,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966816,
      "name": "freq_qos_add_request",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954736,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954736,
      "name": "freq_qos_add_request",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957456,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957456,
      "name": "freq_qos_add_request",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086816,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086816,
      "name": "freq_qos_add_request",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223536,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223536,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580414448,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:528",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414448,
      "name": "freq_qos_add_request",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483136,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:533",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483136,
      "name": "freq_qos_add_request",
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542976,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:538",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542976,
      "name": "freq_qos_add_request",
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491129584,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491129584,
      "name": "freq_qos_add_request",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225127432,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225127432,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284019808,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284019808,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271700322,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271700322,
      "name": "freq_qos_add_request",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893952,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893952,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828912,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828912,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882112,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882112,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
```

```json
{
  "name": "freq_qos_add_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927792,
      "name": "freq_qos_add_request",
      "external": true,
      "loc": "kernel/power/qos.c:753",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927792,
      "name": "freq_qos_add_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int freq_qos_add_request(struct freq_constraints * qos, struct freq_qos_request * req, enum freq_qos_req_type type, s32 value)
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
