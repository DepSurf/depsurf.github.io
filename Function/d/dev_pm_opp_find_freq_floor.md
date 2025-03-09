# Function: <code>dev_pm_opp_find_freq_floor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": false,
      "loc": "include/linux/pm_opp.h:95",
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
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": false,
      "loc": "include/linux/pm_opp.h:119",
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
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": false,
      "loc": "include/linux/pm_opp.h:173",
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
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": false,
      "loc": "include/linux/pm_opp.h:187",
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587055232,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:480",
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
      "addr": 18446744071587055232,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355232,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:487",
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
      "addr": 18446744071587355232,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587534672,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:471",
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
      "addr": 18446744071587534672,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:486",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813296,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587808464,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018610,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588013632,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877651,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588867904,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596821,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588884240,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:613",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539802,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588771840,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:613",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654231,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071589463728,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:541",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538786,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071590940928,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592641456,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:674",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592641456,
      "name": "dev_pm_opp_find_freq_floor",
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593071952,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:677",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593071952,
      "name": "dev_pm_opp_find_freq_floor",
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593823648,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:732",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593823648,
      "name": "dev_pm_opp_find_freq_floor",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501270104,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501270104,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233760244,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/devfreq/devfreq.c:find_available_max_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233760244,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294791680,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/devfreq/devfreq.c:find_available_max_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294791680,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277946352,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/devfreq/devfreq.c:find_available_max_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277946352,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643602,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587638624,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417474,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587412496,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974754,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587969776,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
```

```json
{
  "name": "dev_pm_opp_find_freq_floor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_floor",
      "external": true,
      "loc": "drivers/opp/core.c:534",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090130,
      "name": "dev_pm_opp_find_freq_floor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588085152,
      "name": "dev_pm_opp_find_freq_floor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct dev_pm_opp * dev_pm_opp_find_freq_floor(struct device * dev, long unsigned int * freq)
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
