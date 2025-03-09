# Function: <code>class_for_each_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584403664,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:365",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_suspend_prepare",
        "drivers/regulator/core.c:regulator_suspend_finish",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/power/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403664,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739008,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:365",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_suspend_finish",
        "drivers/regulator/core.c:regulator_suspend_prepare",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739008,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584928896,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:380",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_suspend_finish",
        "drivers/regulator/core.c:regulator_suspend_prepare",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584928896,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585013632,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:347",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_suspend_finish",
        "drivers/regulator/core.c:regulator_suspend_prepare",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013632,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585435888,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:347",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_suspend_finish",
        "drivers/regulator/core.c:regulator_suspend_prepare",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435888,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585679024,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:345",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_resume_early",
        "drivers/regulator/core.c:regulator_suspend_late",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679024,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585809264,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:345",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585809264,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586042496,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042496,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586190128,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190128,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951904,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:352",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951904,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036880,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:352",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_summary_lock",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036880,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920672,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:352",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920672,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483072,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:352",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483072,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588804944,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:352",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588804944,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302288,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:357",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302288,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int class_for_each_device(const struct class * class, const struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590622368,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:387",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_probing_done",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590622368,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int class_for_each_device(const struct class * class, const struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590981616,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:386",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/core.c:fw_devlink_probing_done",
        "drivers/base/core.c:fw_devlink_drivers_done",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_get_property_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981616,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498990016,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498990016,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231558196,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231558196,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292143264,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292143264,
      "name": "class_for_each_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276364848,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276364848,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950496,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950496,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799552,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799552,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586140144,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140144,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int class_for_each_device(struct class * class, struct device * start, void * data, int (*)(struct device *, void *) fn)
```

```json
{
  "name": "class_for_each_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586248832,
      "name": "class_for_each_device",
      "external": true,
      "loc": "drivers/base/class.c:351",
      "file": "drivers/base/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_init_complete_work_function",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_summary_show_subtree",
        "drivers/regulator/core.c:regulator_register",
        "drivers/base/devcoredump.c:devcoredump_exit",
        "drivers/base/devcoredump.c:disabled_store",
        "drivers/power/supply/power_supply_core.c:power_supply_set_input_current_limit_from_supplier",
        "drivers/power/supply/power_supply_core.c:power_supply_is_system_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_am_i_supplied",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586248832,
      "name": "class_for_each_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device * start</code> ➡️ <code>const struct device * start</code>
</li>
</ul>
</details>
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
