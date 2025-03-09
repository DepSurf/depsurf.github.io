# Function: <code>rdmsr_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151088,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:34",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151088,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446448,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:34",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446448,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574096,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:34",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574096,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612992,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:34",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612992,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858992,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:35",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858992,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059456,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059456,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143584,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143584,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333712,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333712,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468384,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468384,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032128,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032128,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184016,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184016,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065968,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065968,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585512704,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512704,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663184,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663184,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911136,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911136,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185088,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185088,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477088,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477088,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584437136,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437136,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372160,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372160,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584420048,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420048,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```

```json
{
  "name": "rdmsr_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526096,
      "name": "rdmsr_on_cpu",
      "external": true,
      "loc": "arch/x86/lib/msr-smp.c:36",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:show_error_count",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq",
        "drivers/cpufreq/speedstep-centrino.c:get_cur_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526096,
      "name": "rdmsr_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdmsr_on_cpu(unsigned int cpu, u32 msr_no, u32 * l, u32 * h)
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
