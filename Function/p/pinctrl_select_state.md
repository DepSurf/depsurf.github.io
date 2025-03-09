# Function: <code>pinctrl_select_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159584,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:986",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_select_state",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159584,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456240,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:999",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_select_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456240,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583984,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:999",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_select_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583984,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622848,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1196",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_force_default",
        "drivers/pinctrl/core.c:pinctrl_force_sleep",
        "drivers/pinctrl/core.c:pinctrl_select_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622848,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583869290,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1271",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869232,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584069834,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1271",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069776,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584154522,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1299",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154464,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584350014,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1288",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344608,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584484850,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479424,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585150833,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1317",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143792,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585302145,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1318",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294928,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585186145,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1341",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182512,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585640033,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1341",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637200,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586800990,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1341",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797792,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587937442,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1341",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ],
      "caller_func": [
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934672,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588211682,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1345",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ],
      "caller_func": [
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208848,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588504482,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1359",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_claim_hogs",
        "drivers/pinctrl/core.c:pinctrl_pm_select_idle_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state",
        "drivers/pinctrl/core.c:pinctrl_pm_select_default_state",
        "drivers/pinctrl/core.c:pinctrl_init_done",
        "drivers/pinctrl/core.c:pinctrl_commit_state"
      ],
      "caller_func": [
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery",
        "drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501648,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496503080,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_shutdown",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_set_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496496264,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229809024,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_unprepare_recovery",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_prepare_recovery",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling",
        "sound/soc/soc-dapm.c:dapm_pinctrl_event",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229802844,
      "name": "pinctrl_select_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290714536,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290702672,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275421902,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275415690,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584453602,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448176,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584389282,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383856,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584436514,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431088,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int pinctrl_select_state(struct pinctrl * p, struct pinctrl_state * state)
```

```json
{
  "name": "pinctrl_select_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584542642,
      "name": "pinctrl_select_state",
      "external": true,
      "loc": "drivers/pinctrl/core.c:1316",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_enable",
        "drivers/pinctrl/core.c:pinctrl_pm_select_state",
        "drivers/pinctrl/core.c:pinctrl_init_done"
      ],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_commit_state",
        "drivers/base/pinctrl.c:pinctrl_bind_pins",
        "drivers/base/pinctrl.c:pinctrl_bind_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537216,
      "name": "pinctrl_select_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
