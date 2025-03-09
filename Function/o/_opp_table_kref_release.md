# Function: <code>_opp_table_kref_release</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587052616,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:862",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587350888,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:869",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587529860,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:920",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587804372,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:994",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588009396,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588863008,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1126",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_put_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863008,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878816,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1207",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878816,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588765760,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1361",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765760,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1371",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457376,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071592653239,
      "name": "_opp_table_kref_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1516",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590934528,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071594537888,
      "name": "_opp_table_kref_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1488",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/opp/core.c:dev_pm_opp_set_opp",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:_find_key",
        "drivers/opp/core.c:dev_pm_opp_get_opp_count",
        "drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq",
        "drivers/opp/core.c:dev_pm_opp_get_max_transition_latency",
        "drivers/opp/core.c:dev_pm_opp_get_max_volt_latency"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592637200,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071596313112,
      "name": "_opp_table_kref_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593067712,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1504",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593067712,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void _opp_table_kref_release(struct kref * kref)
```

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593818912,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1615",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818912,
      "name": "_opp_table_kref_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501265096,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233755772,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294785712,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277942066,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587634388,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587408260,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587965540,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
  "name": "_opp_table_kref_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588080916,
      "name": "_opp_table_kref_release",
      "external": false,
      "loc": "drivers/opp/core.c:1043",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_put_opp_table"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void _opp_table_kref_release(struct kref * kref)
```
</details>
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
