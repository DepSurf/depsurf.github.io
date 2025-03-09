# Function: <code>freq_qos_remove_request</code>

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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922064,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922064,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965904,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965904,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953840,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953840,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956560,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/powercap/dtpm_cpu.c:pd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956560,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085920,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/powercap/dtpm_cpu.c:pd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085920,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222464,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222464,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580413280,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:590",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413280,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481968,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:595",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481968,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541808,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:600",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_exit",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541808,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491129896,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491129896,
      "name": "freq_qos_remove_request",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225127776,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225127776,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284020224,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284020224,
      "name": "freq_qos_remove_request",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271700576,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271700576,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894176,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894176,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829136,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829136,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882336,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882336,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int freq_qos_remove_request(struct freq_qos_request * req)
```

```json
{
  "name": "freq_qos_remove_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579928016,
      "name": "freq_qos_remove_request",
      "external": true,
      "loc": "kernel/power/qos.c:815",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928016,
      "name": "freq_qos_remove_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int freq_qos_remove_request(struct freq_qos_request * req)
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
