# Function: <code>dev_pm_opp_find_freq_exact</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587054912,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:363",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054912,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353344,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:370",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353344,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587533040,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:354",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533040,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812893,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587807184,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018187,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588012208,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877500,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588866944,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596598,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588882992,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:399",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539501,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588769952,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:399",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592653903,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071589461968,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:424",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538495,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071590939520,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592640832,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:616",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592640832,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593071328,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:619",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593071328,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593822640,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:618",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593822640,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501268232,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501268232,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233758504,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233758504,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294789936,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294789936,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277944790,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277944790,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587643179,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587637200,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417051,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587411072,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974331,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587968352,
      "name": "dev_pm_opp_find_freq_exact",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
```

```json
{
  "name": "dev_pm_opp_find_freq_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_find_freq_exact",
      "external": true,
      "loc": "drivers/opp/core.c:369",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089707,
      "name": "dev_pm_opp_find_freq_exact.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588083728,
      "name": "dev_pm_opp_find_freq_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct dev_pm_opp * dev_pm_opp_find_freq_exact(struct device * dev, long unsigned int freq, bool available)
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
