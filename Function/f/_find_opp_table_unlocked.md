# Function: <code>_find_opp_table_unlocked</code>

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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053760,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:50",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053760,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587352112,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:48",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587352112,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531568,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:48",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531568,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587805696,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805696,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010720,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010720,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865264,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_dev_pm_opp_find_and_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_add",
        "drivers/opp/core.c:dev_pm_opp_attach_genpd",
        "drivers/opp/core.c:dev_pm_opp_set_clkname",
        "drivers/opp/core.c:dev_pm_opp_set_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_prop_name",
        "drivers/opp/core.c:dev_pm_opp_set_supported_hw",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
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
      "addr": 18446744071588865264,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880896,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:51",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
        "drivers/opp/core.c:_add_opp_table_indexed",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880896,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767840,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:55",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767840,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459488,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:55",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459488,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590936880,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:55",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590936880,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592638928,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:59",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      "addr": 18446744071592638928,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593069424,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:56",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      "addr": 18446744071593069424,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593820736,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:56",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_remove_table",
        "drivers/opp/core.c:dev_pm_opp_unregister_notifier",
        "drivers/opp/core.c:dev_pm_opp_register_notifier",
        "drivers/opp/core.c:dev_pm_opp_sync_regulators",
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_remove_all_dynamic",
        "drivers/opp/core.c:dev_pm_opp_remove",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
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
      "addr": 18446744071593820736,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501264632,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501264632,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233755428,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233755428,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294784128,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294784128,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277941058,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_opp_get_opp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277941058,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587635712,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635712,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587409584,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409584,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966864,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966864,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
```

```json
{
  "name": "_find_opp_table_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082240,
      "name": "_find_opp_table_unlocked",
      "external": false,
      "loc": "drivers/opp/core.c:45",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082240,
      "name": "_find_opp_table_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct opp_table * _find_opp_table_unlocked(struct device * dev)
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
