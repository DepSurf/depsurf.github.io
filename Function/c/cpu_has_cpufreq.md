# Function: <code>cpu_has_cpufreq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583753754,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753754,
      "name": "cpu_has_cpufreq.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583753829,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584079843,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079843,
      "name": "cpu_has_cpufreq.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584079918,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584222428,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222428,
      "name": "cpu_has_cpufreq.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584222503,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584294990,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294384,
      "name": "cpu_has_cpufreq.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584693758,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584693152,
      "name": "cpu_has_cpufreq.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919440,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919440,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585023344,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:74",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023344,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585227072,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:61",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227072,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363504,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363504,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586071440,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071440,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586192976,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:56",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192976,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068272,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:56",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068272,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:54",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562592,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071592417267,
      "name": "cpu_has_cpufreq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587822593,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:54",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589147313,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:54",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589439697,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:54",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589747665,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:65",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_max_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163360,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163360,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077552,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077552,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585315088,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315088,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int cpu_has_cpufreq(unsigned int cpu)
```

```json
{
  "name": "cpu_has_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421232,
      "name": "cpu_has_cpufreq",
      "external": false,
      "loc": "drivers/acpi/processor_thermal.c:60",
      "file": "drivers/acpi/processor_thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_set_cur_state",
        "drivers/acpi/processor_thermal.c:processor_get_cur_state",
        "drivers/acpi/processor_thermal.c:acpi_processor_max_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421232,
      "name": "cpu_has_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpu_has_cpufreq(unsigned int cpu)
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
