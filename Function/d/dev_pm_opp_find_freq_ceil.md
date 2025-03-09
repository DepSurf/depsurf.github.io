# Function: <code>dev_pm_opp_find_freq_ceil</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": false,
      "loc": "include/linux/pm_opp.h:101",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": false,
      "loc": "include/linux/pm_opp.h:125",
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
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": false,
      "loc": "include/linux/pm_opp.h:179",
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
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": false,
      "loc": "include/linux/pm_opp.h:193",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587055104,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:439",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055104,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587353536,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:446",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353536,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587533232,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:430",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533232,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587812925,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:445",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812925,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587807344,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588018251,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018251,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588012512,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588877322,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:set_freq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877291,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588866080,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591596364,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:set_freq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596333,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588881920,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591539296,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:572",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539265,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588768864,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592653535,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:572",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653504,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589460528,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594538151,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:500",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538151,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590938016,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592641088,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:649",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592641088,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593071584,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:652",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593071584,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593823024,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:679",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593823024,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501268656,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501268656,
      "name": "dev_pm_opp_find_freq_ceil",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233758872,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233758872,
      "name": "dev_pm_opp_find_freq_ceil",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294790480,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294790480,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277945156,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277945156,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587643243,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643243,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587637504,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587417115,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417115,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587411376,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974395,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974395,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587968656,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_ceil",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588089771,
      "name": "dev_pm_opp_find_freq_ceil",
      "external": true,
      "loc": "drivers/opp/core.c:493",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089771,
      "name": "dev_pm_opp_find_freq_ceil.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588084032,
      "name": "dev_pm_opp_find_freq_ceil",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct dev_pm_opp * dev_pm_opp_find_freq_ceil(struct device * dev, long unsigned int * freq)
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
