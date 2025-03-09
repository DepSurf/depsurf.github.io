# Function: <code>cpufreq_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585862704,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2418",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862704,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586261312,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2483",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261312,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586462144,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2432",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586462144,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586544,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2449",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586544,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069840,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2482",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069840,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367136,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2480",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367136,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587547024,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2483",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547024,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821680,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2650",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821680,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026960,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026960,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2690",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588898490,
      "name": "cpufreq_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588885360,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2767",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591597860,
      "name": "cpufreq_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588898080,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2773",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591541451,
      "name": "cpufreq_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588786928,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 783
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2782",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656332,
      "name": "cpufreq_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589479056,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 777
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2822",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594541084,
      "name": "cpufreq_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590959536,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592661824,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2819",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661824,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593092528,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2826",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_register_driver",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593092528,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593845264,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2868",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_register_driver",
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593845264,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501298392,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501298392,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233785056,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233785056,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294826368,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294826368,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1336
    }
  ]
}
```
</details>
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587651952,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651952,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587425824,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425824,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983104,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983104,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
```

```json
{
  "name": "cpufreq_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100848,
      "name": "cpufreq_register_driver",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2644",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100848,
      "name": "cpufreq_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpufreq_register_driver(struct cpufreq_driver * driver_data)
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
