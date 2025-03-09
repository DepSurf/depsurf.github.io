# Function: <code>byt_gpio_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583181398,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:152",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478160,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:730",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478160,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610224,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:730",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610224,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649440,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:730",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649440,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895968,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:733",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895968,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096848,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:733",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096848,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181584,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:726",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_group_simple_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181584,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370608,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:586",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370608,
      "name": "byt_gpio_reg",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505488,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:568",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505488,
      "name": "byt_gpio_reg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585172432,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:558",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172432,
      "name": "byt_gpio_reg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321712,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:558",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321712,
      "name": "byt_gpio_reg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585206128,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:558",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206128,
      "name": "byt_gpio_reg.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585661088,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:558",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661088,
      "name": "byt_gpio_reg.isra.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586823904,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:569",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823904,
      "name": "byt_gpio_reg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587964992,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:569",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964992,
      "name": "byt_gpio_reg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588239504,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:569",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588239504,
      "name": "byt_gpio_reg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588533239,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:556",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469856,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:568",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469856,
      "name": "byt_gpio_reg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400544,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:568",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400544,
      "name": "byt_gpio_reg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457152,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:568",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457152,
      "name": "byt_gpio_reg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```

```json
{
  "name": "byt_gpio_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563280,
      "name": "byt_gpio_reg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:568",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563280,
      "name": "byt_gpio_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * byt_gpio_reg(struct byt_gpio * vg, unsigned int offset, int reg)
```
</details>
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
