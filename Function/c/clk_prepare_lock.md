# Function: <code>clk_prepare_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072928,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:91",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_prepare",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_phase",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_dump_subtree",
        "drivers/clk/clk.c:clk_dump",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_set_rate",
        "drivers/clk/clk.c:__clk_create_clk",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072928,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484512,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:91",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump",
        "drivers/clk/clk.c:clk_dump_subtree",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare",
        "drivers/clk/clk.c:clk_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484512,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291232,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:91",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump",
        "drivers/clk/clk.c:clk_dump_subtree",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare",
        "drivers/clk/clk.c:clk_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291232,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369440,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:91",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump",
        "drivers/clk/clk.c:clk_dump_subtree",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369440,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775296,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:113",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump",
        "drivers/clk/clk.c:clk_dump_subtree",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775296,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003456,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:115",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003456,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585109216,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:113",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585109216,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314944,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:123",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314944,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585459104,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459104,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169200,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:133",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_one",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169200,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287728,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:133",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_one",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287728,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161520,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:133",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161520,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662752,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:133",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662752,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587931728,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:126",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_rate_get",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931728,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288656,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:126",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_rate_get",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288656,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589585488,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:126",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_rate_get",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_subtree",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589585488,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894976,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:126",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_rate_get",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_summary_show_one",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894976,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497742128,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497742128,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230565860,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230565860,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275886444,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_add_hw_provider",
        "drivers/clk/clk.c:of_clk_add_provider",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275886444,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585221632,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221632,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585173808,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585173808,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585409504,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409504,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void clk_prepare_lock()
```

```json
{
  "name": "clk_prepare_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585517040,
      "name": "clk_prepare_lock",
      "external": false,
      "loc": "drivers/clk/clk.c:129",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_max_rate_show",
        "drivers/clk/clk.c:clk_min_rate_show",
        "drivers/clk/clk.c:clk_dump_show",
        "drivers/clk/clk.c:clk_summary_show",
        "drivers/clk/clk.c:clk_core_get_scaled_duty_cycle",
        "drivers/clk/clk.c:clk_set_duty_cycle",
        "drivers/clk/clk.c:clk_core_get_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_get_parent",
        "drivers/clk/clk.c:clk_set_rate_range",
        "drivers/clk/clk.c:clk_core_get_rate",
        "drivers/clk/clk.c:clk_core_get_accuracy",
        "drivers/clk/clk.c:clk_disable_unused",
        "drivers/clk/clk.c:clk_core_disable_unprepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517040,
      "name": "clk_prepare_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clk_prepare_lock()
```
</details>
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
