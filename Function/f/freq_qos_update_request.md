# Function: <code>freq_qos_update_request</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579921968,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921968,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966960,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966960,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954880,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954880,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957600,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957600,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086960,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086960,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223712,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223712,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580414656,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:564",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414656,
      "name": "freq_qos_update_request",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483344,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:569",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483344,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543184,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:574",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_set_boost",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543184,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491129760,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491129760,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225127624,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225127624,
      "name": "freq_qos_update_request",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284020048,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:cpufreq_set_cur_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284020048,
      "name": "freq_qos_update_request",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271700470,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271700470,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894080,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894080,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579829040,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829040,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882240,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882240,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
```

```json
{
  "name": "freq_qos_update_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579927920,
      "name": "freq_qos_update_request",
      "external": true,
      "loc": "kernel/power/qos.c:789",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/intel_pstate.c:update_qos_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927920,
      "name": "freq_qos_update_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int freq_qos_update_request(struct freq_qos_request * req, s32 new_value)
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
