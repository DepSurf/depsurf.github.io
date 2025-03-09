# Function: <code>regulator_lock_nested</code>

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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585168352,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:160",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_suspend_voltage",
        "drivers/regulator/core.c:regulator_set_voltage",
        "drivers/regulator/core.c:_regulator_list_voltage",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168352,
      "name": "regulator_lock_nested.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int regulator_lock_nested(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585290332,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:167",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271968,
      "name": "regulator_lock_nested",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int regulator_lock_nested(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585496374,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482448,
      "name": "regulator_lock_nested",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585630999,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367994,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586486922,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:150",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586370351,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:150",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_opmode_show",
        "drivers/regulator/core.c:regulator_uA_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586886612,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:140",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_lock_recursive"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588175998,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:141",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589573943,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:141",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589877575,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:141",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590215431,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:143",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:requested_microamps_show",
        "drivers/regulator/core.c:state_show",
        "drivers/regulator/core.c:opmode_show",
        "drivers/regulator/core.c:microamps_show",
        "drivers/regulator/core.c:microvolts_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498300024,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230975520,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291459732,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275989660,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585392151,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585262071,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585581399,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
  "name": "regulator_lock_nested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585689479,
      "name": "regulator_lock_nested",
      "external": false,
      "loc": "drivers/regulator/core.c:149",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_summary_lock_one",
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
        "drivers/regulator/core.c:regulator_total_uA_show",
        "drivers/regulator/core.c:regulator_state_show",
        "drivers/regulator/core.c:regulator_uV_show",
        "drivers/regulator/core.c:regulator_lock_recursive"
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int regulator_lock_nested(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int regulator_lock_nested(struct regulator_dev * rdev, struct ww_acquire_ctx * ww_ctx)
```
</details>
</li>
</ul>
