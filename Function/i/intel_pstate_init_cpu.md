# Function: <code>intel_pstate_init_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585900460,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1045",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586301693,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1382",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506544,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1872",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506544,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586631312,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1883",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631312,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114560,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1648",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114560,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1825",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412256,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    },
    {
      "addr": 18446744071587417394,
      "name": "intel_pstate_init_cpu.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1888",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587592352,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    },
    {
      "addr": 18446744071587597586,
      "name": "intel_pstate_init_cpu.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1913",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869696,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071587874323,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1959",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074928,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071588079848,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1967",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933584,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071588941233,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588949088,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2115",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588949088,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832128,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2112",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832128,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589529376,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2273",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529376,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591021152,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2443",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591021152,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592732032,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2407",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592732032,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593169168,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2431",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593169168,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593922704,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:2456",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922704,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1959",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697072,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071587701992,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1959",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587472192,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071587479950,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1959",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031072,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071588035992,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```

```json
{
  "name": "intel_pstate_init_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pstate_init_cpu",
      "external": false,
      "loc": "drivers/cpufreq/intel_pstate.c:1959",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588146624,
      "name": "intel_pstate_init_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
    },
    {
      "addr": 18446744071588151560,
      "name": "intel_pstate_init_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```
</details>
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
int intel_pstate_init_cpu(unsigned int cpunum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pstate_init_cpu(unsigned int cpunum)
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
