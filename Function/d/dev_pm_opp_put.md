# Function: <code>dev_pm_opp_put</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_put",
      "external": false,
      "loc": "include/linux/pm_opp.h:199",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dev_pm_opp_put",
      "external": false,
      "loc": "include/linux/pm_opp.h:199",
      "file": "drivers/devfreq/governor_passive.c",
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052848,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:921",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052848,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587351328,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:928",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351328,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587530464,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1027",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530464,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587805008,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1101",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805008,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010016,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010016,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588876253,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1213",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:set_freq_table",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863904,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884941,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1282",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:set_freq_table",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879200,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772537,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1439",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765632,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464505,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1449",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457248,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590942203,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1594",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934384,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592644107,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1566",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592637040,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593074603,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1574",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593067552,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593826523,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1684",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_table_kref_release",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp",
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818752,
      "name": "dev_pm_opp_put",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501265840,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:_of_opp_free_required_opps",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501265840,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233756496,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request",
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:_of_opp_free_required_opps",
        "drivers/cpufreq/omap-cpufreq.c:omap_target",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_max_freq",
        "drivers/devfreq/devfreq.c:find_available_min_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233756496,
      "name": "dev_pm_opp_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294786624,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:_of_opp_free_required_opps",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_max_freq",
        "drivers/devfreq/devfreq.c:find_available_min_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294786624,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277942644,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:get_voltage",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:_of_opp_free_required_opps",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:find_available_max_freq",
        "drivers/devfreq/devfreq.c:find_available_min_freq",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277942644,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587635008,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635008,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408880,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408880,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966160,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966160,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588081536,
      "name": "dev_pm_opp_put",
      "external": true,
      "loc": "drivers/opp/core.c:1150",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_remove_all_static",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081536,
      "name": "dev_pm_opp_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_put(struct dev_pm_opp * opp)
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
