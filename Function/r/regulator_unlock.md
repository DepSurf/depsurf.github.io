# Function: <code>regulator_unlock</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603114167,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:187",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:_regulator_resume_early",
        "drivers/regulator/core.c:_regulator_suspend_late",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_unlock_supply"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272144,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:223",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272144,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482624,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482624,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623152,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623152,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586346640,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346640,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586464976,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586464976,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586348656,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348656,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586886711,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:195",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869184,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588176103,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:196",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589574178,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:196",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589877810,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:196",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590215666,
      "name": "regulator_unlock",
      "external": false,
      "loc": "drivers/regulator/core.c:198",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_get_error_flags",
        "drivers/regulator/core.c:regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage_rdev",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498281048,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498281048,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230962232,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230962232,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291440528,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291440528,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275978716,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_resolve_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive",
        "drivers/regulator/core.c:regulator_unlock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275978716,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384800,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384800,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585254224,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585254224,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585573552,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585573552,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void regulator_unlock(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681520,
      "name": "regulator_unlock",
      "external": true,
      "loc": "drivers/regulator/core.c:205",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_unlock_one",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_resume",
        "drivers/regulator/core.c:regulator_suspend",
        "drivers/regulator/core.c:regulator_remove_coupling",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_load",
        "drivers/regulator/core.c:regulator_get_error_flags",
        "drivers/regulator/core.c:_regulator_get_mode",
        "drivers/regulator/core.c:regulator_set_mode",
        "drivers/regulator/core.c:_regulator_get_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_dependent",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681520,
      "name": "regulator_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void regulator_unlock(struct regulator_dev * rdev)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void regulator_unlock(struct regulator_dev * rdev)
```
</details>
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
