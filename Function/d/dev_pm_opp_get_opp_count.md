# Function: <code>dev_pm_opp_get_opp_count</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": false,
      "loc": "include/linux/pm_opp.h:88",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": false,
      "loc": "include/linux/pm_opp.h:142",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": false,
      "loc": "include/linux/pm_opp.h:156",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587054752,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:312",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054752,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587355904,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:327",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355904,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587535344,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:311",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535344,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587809232,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809232,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588014400,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014400,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:set_freq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877410,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588866448,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:set_freq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596508,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588882496,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:356",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539411,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588769456,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:356",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653713,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589461152,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:381",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538341,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071590938688,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:425",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596313313,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071592642224,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:428",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842167,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071593072720,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:427",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597767168,
      "name": "dev_pm_opp_get_opp_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071593824640,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501271168,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501271168,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233761112,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233761112,
      "name": "dev_pm_opp_get_opp_count",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294792992,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294792992,
      "name": "dev_pm_opp_get_opp_count",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277947228,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/of.c:dev_pm_opp_of_register_em",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277947228,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639392,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639392,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413264,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413264,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970544,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970544,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dev_pm_opp_get_opp_count(struct device * dev)
```

```json
{
  "name": "dev_pm_opp_get_opp_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085920,
      "name": "dev_pm_opp_get_opp_count",
      "external": true,
      "loc": "drivers/opp/core.c:326",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085920,
      "name": "dev_pm_opp_get_opp_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int dev_pm_opp_get_opp_count(struct device * dev)
```
</details>
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
