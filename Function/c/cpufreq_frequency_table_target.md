# Function: <code>cpufreq_frequency_table_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, struct cpufreq_frequency_table * table, unsigned int target_freq, unsigned int relation, unsigned int * index)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867200,
      "name": "cpufreq_frequency_table_target",
      "external": true,
      "loc": "drivers/cpufreq/freq_table.c:120",
      "file": "drivers/cpufreq/freq_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target",
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target",
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585867200,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586256840,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:837",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274809,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:837",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586463679,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:841",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478970,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:841",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587951,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:845",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603514,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:845",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587071266,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:865",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086746,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:865",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587369570,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:898",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384904,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:898",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587549138,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:890",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564808,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:890",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587824182,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:919",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840584,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:919",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588029494,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045416,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588886469,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:927",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target"
      ]
    },
    {
      "addr": 18446744071588905912,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:927",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588887552,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071588898643,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588904157,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:980",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918491,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:980",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588792667,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:974",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588807096,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:974",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589480432,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:971",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589499736,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:971",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590968824,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1026",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1026",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590960848,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
    },
    {
      "addr": 18446744071594541239,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071590982368,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
    },
    {
      "addr": 18446744071594542203,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592673094,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1026",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1026",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592663456,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
    },
    {
      "addr": 18446744071596313803,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071592687968,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
    },
    {
      "addr": 18446744071596314250,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593103910,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1029",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1029",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593094176,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    },
    {
      "addr": 18446744071596842724,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071593118960,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    },
    {
      "addr": 18446744071596843300,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593856678,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1024",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:1024",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846912,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    },
    {
      "addr": 18446744071597767870,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071593871792,
      "name": "cpufreq_frequency_table_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    },
    {
      "addr": 18446744071597768446,
      "name": "cpufreq_frequency_table_target.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501292612,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501314324,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233780744,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 3233801088,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294819132,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294848220,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587654486,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670408,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587428358,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587444280,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587985638,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001560,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_frequency_table_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588097766,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117000,
      "name": "cpufreq_frequency_table_target",
      "external": false,
      "loc": "include/linux/cpufreq.h:925",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, struct cpufreq_frequency_table * table, unsigned int target_freq, unsigned int relation, unsigned int * index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy * policy, unsigned int target_freq, unsigned int relation)
```
</details>
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
