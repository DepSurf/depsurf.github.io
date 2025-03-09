# Function: <code>dev_pm_opp_get_voltage</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587053184,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053184,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587351648,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:99",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351648,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530784,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:104",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530784,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587812758,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812758,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587805312,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588018052,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018052,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588010336,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588876804,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876804,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588863472,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591595788,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595788,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588878304,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591538960,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:105",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591538960,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588765184,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592653085,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:105",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653085,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589456816,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594537671,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:105",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594537671,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590933776,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592636272,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:121",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592636272,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593066864,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:118",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593066864,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593818112,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:118",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818112,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501266096,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501266096,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233756916,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/cpufreq/omap-cpufreq.c:omap_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233756916,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294787280,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294787280,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277943098,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277943098,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587643044,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643044,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587635328,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587416916,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587416916,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587409200,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974196,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974196,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587966480,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get_voltage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588089572,
      "name": "dev_pm_opp_get_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:101",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089572,
      "name": "dev_pm_opp_get_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588081856,
      "name": "dev_pm_opp_get_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
long unsigned int dev_pm_opp_get_voltage(struct dev_pm_opp * opp)
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
