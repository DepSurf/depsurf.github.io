# Function: <code>regulator_ops_is_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595434005,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:135",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264192,
      "name": "regulator_ops_is_valid.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595686357,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:135",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445952,
      "name": "regulator_ops_is_valid.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596610748,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:135",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529616,
      "name": "regulator_ops_is_valid.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602941109,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:135",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939776,
      "name": "regulator_ops_is_valid.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603113919,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:128",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187322,
      "name": "regulator_ops_is_valid.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604916609,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:135",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303806,
      "name": "regulator_ops_is_valid.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605025253,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585490064,
      "name": "regulator_ops_is_valid.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585630970,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630656,
      "name": "regulator_ops_is_valid.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367952,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage",
        "drivers/regulator/core.c:regulator_check_voltage"
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
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586486880,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:126",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage",
        "drivers/regulator/core.c:regulator_check_voltage"
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
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586370331,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:126",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage",
        "drivers/regulator/core.c:regulator_check_voltage"
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
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586886592,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:116",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage",
        "drivers/regulator/core.c:regulator_check_voltage"
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
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588175968,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:117",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool regulator_ops_is_valid(struct regulator_dev * rdev, int ops)
```

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589573916,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:117",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589568368,
      "name": "regulator_ops_is_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
bool regulator_ops_is_valid(struct regulator_dev * rdev, int ops)
```

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589877548,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:117",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589870416,
      "name": "regulator_ops_is_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
bool regulator_ops_is_valid(struct regulator_dev * rdev, int ops)
```

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590215404,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:119",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_sync_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208256,
      "name": "regulator_ops_is_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498299976,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498320312,
      "name": "regulator_ops_is_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230975484,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231001244,
      "name": "regulator_ops_is_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291459672,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291452752,
      "name": "regulator_ops_is_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275989624,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276009884,
      "name": "regulator_ops_is_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585392122,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391808,
      "name": "regulator_ops_is_valid.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585262042,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261728,
      "name": "regulator_ops_is_valid.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585581370,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585581056,
      "name": "regulator_ops_is_valid.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regulator_ops_is_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689450,
      "name": "regulator_ops_is_valid",
      "external": false,
      "loc": "drivers/regulator/core.c:125",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_disable",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_late_cleanup",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_set_current_limit",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:create_regulator",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_mode_constrain",
        "drivers/regulator/core.c:regulator_check_voltage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689136,
      "name": "regulator_ops_is_valid.part.0",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool regulator_ops_is_valid(struct regulator_dev * rdev, int ops)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
