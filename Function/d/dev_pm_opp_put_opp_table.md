# Function: <code>dev_pm_opp_put_opp_table</code>

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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052576,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:886",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052576,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587350848,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:893",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_put",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587350848,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587529808,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:979",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_put_genpd_virt_dev",
        "drivers/opp/core.c:dev_pm_opp_set_genpd_virt_dev",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529808,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1053",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812644,
      "name": "dev_pm_opp_put_opp_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587804320,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009344,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009344,
      "name": "dev_pm_opp_put_opp_table",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588876561,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1165",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863856,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588883718,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1247",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_bw",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879152,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588769390,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1404",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766224,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589461084,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1414",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457840,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590938605,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1559",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:devm_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:devm_pm_opp_register_set_opp_helper",
        "drivers/opp/core.c:devm_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:devm_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release",
        "drivers/devfreq/governor_passive.c:devfreq_passive_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934992,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592641853,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1531",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release",
        "drivers/devfreq/governor_passive.c:devfreq_passive_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592637680,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593072346,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1539",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release",
        "drivers/devfreq/governor_passive.c:devfreq_passive_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593068176,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593825100,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1649",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add_dynamic",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:_opp_remove_all",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/devfreq/devfreq.c:devfreq_dev_release",
        "drivers/devfreq/governor_passive.c:devfreq_passive_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593819376,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501265016,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_del_provider",
        "drivers/base/power/domain.c:of_genpd_add_provider_onecell",
        "drivers/base/power/domain.c:of_genpd_add_provider_simple",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501265016,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233755728,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_del_provider",
        "drivers/base/power/domain.c:of_genpd_add_provider_onecell",
        "drivers/base/power/domain.c:of_genpd_add_provider_simple",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table",
        "drivers/opp/of.c:_opp_table_free_required_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233755728,
      "name": "dev_pm_opp_put_opp_table",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294785600,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_del_provider",
        "drivers/base/power/domain.c:of_genpd_add_provider_onecell",
        "drivers/base/power/domain.c:of_genpd_add_provider_simple",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table",
        "drivers/opp/of.c:_opp_table_free_required_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294785600,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277941992,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:of_genpd_del_provider",
        "drivers/base/power/domain.c:of_genpd_add_provider_onecell",
        "drivers/base/power/domain.c:of_genpd_add_provider_simple",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus",
        "drivers/opp/of.c:of_get_required_opp_performance_state",
        "drivers/opp/of.c:dev_pm_opp_of_add_table_indexed",
        "drivers/opp/of.c:dev_pm_opp_of_add_table",
        "drivers/opp/of.c:_opp_table_free_required_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277941992,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587634336,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634336,
      "name": "dev_pm_opp_put_opp_table",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408208,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408208,
      "name": "dev_pm_opp_put_opp_table",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965488,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965488,
      "name": "dev_pm_opp_put_opp_table",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
```

```json
{
  "name": "dev_pm_opp_put_opp_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588080864,
      "name": "dev_pm_opp_put_opp_table",
      "external": true,
      "loc": "drivers/opp/core.c:1102",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_detach_genpd",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper",
        "drivers/opp/core.c:dev_pm_opp_put_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_put_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_clock_latency",
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus",
        "drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080864,
      "name": "dev_pm_opp_put_opp_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void dev_pm_opp_put_opp_table(struct opp_table * opp_table)
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
