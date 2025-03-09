# Function: <code>regulator_get_voltage_rdev</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585499668,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3979",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516999,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585499536,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585631396,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658065,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585631264,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4028",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382253,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586361360,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4164",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591454418,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586479120,
      "name": "regulator_get_voltage_rdev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4166",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591396190,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586362528,
      "name": "regulator_get_voltage_rdev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4289",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:microvolts_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592440941,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586871712,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4334",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:microvolts_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594309185,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588159984,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4364",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:microvolts_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596231465,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589577728,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4430",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:microvolts_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596759373,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589879648,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:4436",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_voltage_rdev",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_get_optimal_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:regulator_is_supported_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints_debug",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:drms_uA_update",
        "drivers/regulator/core.c:microvolts_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597667844,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590217504,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498288656,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498288656,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230969432,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:machine_constraints_voltage",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230969432,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291453232,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291453232,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275985642,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275985642,
      "name": "regulator_get_voltage_rdev",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585392548,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418986,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585392416,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585262468,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289137,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585262336,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585581796,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608465,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585581664,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```

```json
{
  "name": "regulator_get_voltage_rdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689876,
      "name": "regulator_get_voltage_rdev",
      "external": true,
      "loc": "drivers/regulator/core.c:3988",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_get_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_balance_voltage",
        "drivers/regulator/core.c:regulator_set_voltage_rdev",
        "drivers/regulator/core.c:regulator_set_voltage_unlocked",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_call_set_voltage_sel",
        "drivers/regulator/core.c:print_constraints",
        "drivers/regulator/core.c:regulator_uV_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716593,
      "name": "regulator_get_voltage_rdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585689744,
      "name": "regulator_get_voltage_rdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev * rdev)
```
</details>
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
