# Function: <code>work_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480096,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4610",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480096,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493920,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4698",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493920,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513344,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4728",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513344,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501792,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4748",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:call_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501792,
      "name": "work_on_cpu",
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527808,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4774",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:call_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527808,
      "name": "work_on_cpu",
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555600,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4891",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555600,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593216,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:4914",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593216,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618896,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5059",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618896,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642576,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642576,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673196,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5116",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669488,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579653020,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5137",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649328,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659404,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5144",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655616,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736380,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5197",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732640,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842090,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5182",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841776,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979882,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5191",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974656,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028986,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5584",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/cpu.c:cpu_down_maps_locked",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025792,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490809480,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490809480,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224844404,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224844404,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283645440,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283645440,
      "name": "work_on_cpu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271484856,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_on_cpu_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271484856,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618880,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618880,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547264,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547264,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616160,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616160,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```

```json
{
  "name": "work_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649744,
      "name": "work_on_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:5093",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe",
        "kernel/workqueue.c:work_on_cpu_safe",
        "drivers/pci/pci-driver.c:pci_device_probe",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649744,
      "name": "work_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
long int work_on_cpu(int cpu, long int (*)(void *) fn, void * arg)
```
</details>
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
